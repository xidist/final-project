
link to editable/playable hydra sketch:

https://hydra.ojack.xyz/?sketch_id=hTDYMbGAXIOhsPIJ



gif

[![Image from Gyazo](https://i.gyazo.com/95e08032363a579ff5f6d4d1792b3fc9.gif)](https://gyazo.com/95e08032363a579ff5f6d4d1792b3fc9)

![alttext](media/another4.gif)

code

```

src(o0).diff(o3,0.9)
  .mask(shape(4,0.4,0.4))
.scale(1.002)
.modulate(noise(2,0.1))
.modulateHue(src(o1).scrollX(0.5,0), 1)
.layer(
		voronoi(4, 0.2, 0.5)
 		.mult(osc(10,2, ({time}) => Math.tan(time/20)*100 ) )
  		.saturate(() => Math.sin(time)*10)
		.luma(0.7)
  		//.layer(Math.min(osc(13,0.5,5), src(s1)))
		
)
  .out(o0)

s1.initImage("https://upload.wikimedia.org/wikipedia/commons/2/25/Hydra-Foto.jpg")
osc(9, 2, 8).modulate(src(s1),5).out(o1)


s2.initCam()
src(s2)
	.diff(
	osc(10,1,1)
  .rotate( () => time%30, () => Math.sin(time*0.01)*0.09 )
)
  .out(o2)


s3.initVideo("https://cdn.glitch.global/e764fb49-9460-4375-9503-543e60b9dfd4/5b97993b0327636dfabac77adbc97cd8.mp4?v=1669843575186")
src(s3).modulate(noise(3)).colorama(.9).diff(osc(() => -mouse.x * 0.05/ width,
  () => -mouse.y.ease('easeInOutCubic') / height,5))
  .layer(src(o3).mask(shape(2*Math.sin(time), 0.4, 0))).kaleid(()=>6+Math.sin(time)*2)
          .scrollX([0.005, -0.005])
          .scrollY(0.005)
  .out(o3)

render()

```


adding more to it

[![Image from Gyazo](https://i.gyazo.com/5d9164deb8231a473ca3d30508d2a202.gif)](https://gyazo.com/5d9164deb8231a473ca3d30508d2a202)

```

await loadScript("https://threejs.org/build/three.js")
scene = new THREE.Scene()
camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000)
renderer = new THREE.WebGLRenderer()
renderer.setSize(width, height)
geometry = new THREE.TorusKnotGeometry()
material = new THREE.MeshNormalMaterial()
m = new THREE.Mesh(geometry, material);
scene.add(m)
camera.position.z = 5.5
// 'update' is a reserved function that will be run every time the main hydra rendering context is updated
update = () => {
  m.rotation.x += 0.01;
  m.rotation.y += 0.01;
  m.rotation.z += 0.01 * Math.sin(time);
  renderer.render( scene, camera );
}
s0.init({ src: renderer.domElement }) //setting s0 to the twisted torus
src(s0)
  .layer(src(s0)
       	.modulateRotate(src(s0).colorama(.9), 8)
         )
	.modulate(src(o2), 0.04)
	.repeatX(4, () => Math.sin(time))
	.layer(src(s0).luma([0.6,0.4,0.2,0.1].fast(2)).invert().repeatY(5, () => Math.cos(time))) //taking torus
  .out(o0)
s1.initImage("https://upload.wikimedia.org/wikipedia/commons/2/25/Hydra-Foto.jpg")
osc(9, 2, 8).modulate(src(s1),5)
	.diff(src(o2)
      .modulateScale(osc(1.5, 2, 3), 20, 0).thresh(0.4, 0.3)
         )
  .out(o1)

render()

```