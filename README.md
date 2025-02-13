# Final Project! An Audio Visuals Demo

This is it! The culmination of your procedural graphics experience this semester. For your final project, we'd like to give you the time and space to explore a topic of your choosing. You may choose any topic you please, so long as you vet the topic and scope with an instructor or TA. We've provided some suggestions below. The scope of your project should be roughly 1.5 homework assignments). To help structure your time, we're breaking down the project into 4 milestones:

## Project planning: Design Doc (due 11/9)
Before submitting your first milestone, _you must get your project idea and scope approved by Rachel, Adam or a TA._

### Design Doc
Start off by forking this repository. In your README, write a design doc to outline your project goals and implementation plan. It must include the following sections:

#### Introduction
- What motivates your project?
- I am interested in the algorave/livecode movement and want to experiment with music that is synced with some visual input. 

**intro examples!**

[char stiles reel](https://www.youtube.com/watch?v=lEJiP4JGEh0&t=16s)


https://user-images.githubusercontent.com/60904107/201157608-cd741ffc-f59f-4ed5-b39f-857d01d376a4.mp4



[pd+gem - live visuals](https://www.youtube.com/watch?v=y1rBa_STq64)

https://user-images.githubusercontent.com/60904107/201159128-5848e037-ce36-4a50-bf04-42090c8dabb7.mp4



#### Goal
- What do you intend to achieve with this project?

My main goal is to experiment and have fun exploring a bunch of techniques. I've been interested in creative coding for a while, but just never really had the time or wherewithal to commit to a project. I'm intersted in possibly creating a procedufral tool to generate music and visuals that are tied to it in some way. A goal for a much larger project would be to incorporate the [tidal cycles library](https://tidalcycles.org/docs/showcase) to generate music cycles (patterns/blocks) and visual loops that correspond to the cycles. This would be a midi/keyboard/mouse or some sort of i/o input to coordinate with the music/visual generator/engine. 
  <img width="767" alt="image" src="https://user-images.githubusercontent.com/60904107/201146535-cbe55833-7998-4bd4-90af-28c96b18e1a5.png">
  
A much more scope friendly goal in terms of something that I can work on in this class, would be to create a 1 minute demo exploring some of the tools that I would like to leverage later. Instead of creating a whole procedural visual/audio program, I can record/stage a shader-demo-scene-esque performance that utilizes some video/audio tools in the procedral art creation.
 
 

#### Inspiration/reference:
- You must have some form of reference material for your final project. Your reference may be a research paper, a blog post, some artwork, a video, another class at Penn, etc.  
- Include in your design doc links to and images of your reference material.

[Char Stiles](http://charstiles.com/) is one of my references. She's pretty involved in the algorave community and has tutorials on her personal site on how to get started. She also did some [really cool](https://www.youtube.com/watch?v=WQgqvNyITWM) audio based visual sfor Crystal Castles' music video *fleece*.


[![IMAGE_ALT](https://img.youtube.com/vi/WQgqvNyITWM/0.jpg)](https://www.youtube.com/watch?v=WQgqvNyITWM)



https://user-images.githubusercontent.com/60904107/201155609-ba173746-8311-417f-8c5b-014593effbb4.mp4



here is a hydra mash of shaders that i would love to modify with some audio inputs.
[this twitter page](https://twitter.com/hydra_patterns), is a bot that acts almost as a shadertoy-esque showcase on some cool hydra shaders.
https://hydra.ojack.xyz/?sketch_id=YqShZ3C0254WQi0b

https://user-images.githubusercontent.com/60904107/201144258-c4a62023-41af-4b54-bc9f-7163d838b046.mp4

https://hydra.ojack.xyz/?sketch_id=DvH3S9lsUSudiUYo

https://user-images.githubusercontent.com/60904107/201149941-53c42daf-e0fe-4321-a5a9-4106c4b3f76c.mp4



https://hydra.ojack.xyz/?code=JTJGJTJGJTIwbGljZW5zZWQlMjB3aXRoJTIwQ0MlMjBCWS1OQy1TQSUyMDQuMCUyMGh0dHBzJTNBJTJGJTJGY3JlYXRpdmVjb21tb25zLm9yZyUyRmxpY2Vuc2VzJTJGYnktbmMtc2ElMkY0LjAlMkYlMEElMkYlMkYlMjAlMjJlZ2clMjBvZiUyMHRoZSUyMHBob2VuaXglMjIlMEElMkYlMkYlMjBBbGV4YW5kcmUlMjBSYW5nZWwlMEElMkYlMkYlMjB3d3cuYWxleGFuZHJlcmFuZ2VsLmFydC5iciUyRmh5ZHJhLmh0bWwlMEElMEFzcGVlZCUzRDEuMiUwQXNoYXBlKDk5JTJDLjE1JTJDLjUpLmNvbG9yKDAlMkMxJTJDMiklMEElMEEuZGlmZiglMjBzaGFwZSgyNDAlMkMuNSUyQzApLnNjcm9sbFgoLjA1KS5yb3RhdGUoJTIwKCklM0QlM0V0aW1lJTJGMSUyMCkuY29sb3IoMSUyQzAlMkMuNzUpLmludmVydCgpJTIwKSUwQS5kaWZmKCUyMHNoYXBlKDk5JTJDLjQlMkMuMDAyKS5zY3JvbGxYKC4xMCkucm90YXRlKCUyMCgpJTNEJTNFdGltZSUyRjIlMjApLmNvbG9yKDElMkMwJTJDLjc1KSUyMCklMEEuZGlmZiglMjBzaGFwZSg5OSUyQy4zJTJDLjAwMikuc2Nyb2xsWCguMTUpLnJvdGF0ZSglMjAoKSUzRCUzRXRpbWUlMkYzJTIwKS5jb2xvcigxJTJDMCUyQy43NSkuaW52ZXJ0KCklMjApJTBBLmRpZmYoJTIwc2hhcGUoOTklMkMuMiUyQy4wMDIpLnNjcm9sbFgoLjIwKS5yb3RhdGUoJTIwKCklM0QlM0V0aW1lJTJGNCUyMCkuY29sb3IoMSUyQzAlMkMuNzUpJTIwKSUwQS5kaWZmKCUyMHNoYXBlKDk5JTJDLjElMkMuMDAyKS5zY3JvbGxYKC4yNSkucm90YXRlKCUyMCgpJTNEJTNFdGltZSUyRjUlMjApLmNvbG9yKDElMkMwJTJDLjc1KSUyMCklMEElMEEubW9kdWxhdGVTY2FsZSglMEElMjAlMjBzaGFwZSgyNDAlMkMuNSUyQzApLmludmVydCgpLnNjcm9sbFgoLjA1KS5yb3RhdGUoJTIwKCklM0QlM0V0aW1lJTJGMTAlMjApJTBBJTIwJTIwJTJDJTIwKCklM0QlM0UoTWF0aC5zaW4odGltZSUyRjMpKi4yKSUyQi4yJTIwKSUwQSUwQS5zY2FsZSgxLjYlMkMuNiUyQzEpLmludmVydCgpJTBBLm91dCgpJTBB


https://user-images.githubusercontent.com/60904107/201151264-e4371ec4-e70b-4671-8cc1-3fdb1df3568d.mp4

the above is actually edited code, that's why the link is so long. the url has a "code=" tag, similar to the img width and height tags in markdown. It looks like the code is just encrypted into a alpanumeric string.

here is the original link:
https://hydra.ojack.xyz/?sketch_id=mkhZSOzTG3DlWBsE



#### Specification:
- Outline the main features of your project.

![image](https://user-images.githubusercontent.com/60904107/201156213-7788617a-38ce-499e-ad54-549b6f178f05.png)

if time permitting: an additional 6th feature would be to utilize the hydra [initVideo](https://hydra.ojack.xyz/api/#functions/initVideo/0) stream to create a shader that manipulates a song's music video (can rip from yt) based on it's audio/spectral information. this might even be another project on its own.

![2ad6e057ee6e654d7b87fa4582f45ef8](https://user-images.githubusercontent.com/60904107/201162143-b5419249-1b28-46e4-819b-daa55b3c72a5.gif)





#### Techniques:
- What are the main technical/algorithmic tools you’ll be using? Give an overview, citing specific papers/articles.

![image](https://user-images.githubusercontent.com/60904107/201155932-5674304b-c0b9-4b71-a8f1-73d95f29fd25.png)


here is an initial test with some hydra code. i like how easy it is to generate some output with this tool. it also just runs in browser, which is handy. I am thinking of starting with this one to draft some audio/visual ideas. the thing i like about hydra as well, is that you can [import any js library in it, as a packaged script](https://hydra.ojack.xyz/docs/#/additional_topics?id=loading-external-scripts). this means that i can also import three.js for some visual computation/functuons and also p5.js for some extra visual library tools. 

![305edb327e31d02f82a7d0a4d5ad5627](https://user-images.githubusercontent.com/60904107/201142297-c45aa814-4057-4071-9f06-bfe7140ee007.gif)

#### Design:
- How will your program fit together? Make a simple free-body diagram illustrating the pieces.

![5449fce4c1f4c08701d0219999d8b231](https://user-images.githubusercontent.com/60904107/201170941-b1ad097d-c755-4930-b5c3-79bfc4e6b611.gif)

higher res (readable) screenshot of free body diagram (rip gifs):
![image](https://user-images.githubusercontent.com/60904107/201172988-9b1a7f50-53df-45bd-b65b-fb225981c047.png)


#### Timeline:
- Create a week-by-week set of milestones for each person in your group. Make sure you explicitly outline what each group member's duties will be.

here is a proposed timeline:

<img width="1221" alt="image" src="https://user-images.githubusercontent.com/60904107/201178579-bfe87408-8465-4c90-a31c-5af9e287cd33.png">

i used this site called [toggl](https://toggl.com/) to make a timeline/ management system for this project. if the timeline changes, i will make sure to update it in th readme and adjust depending on project progress.

Submit your Design doc as usual via pull request against this repository.
## Milestone 1: Implementation part 1 (due 11/16)
Begin implementing your engine! Don't worry too much about polish or parameter tuning -- this week is about getting together the bulk of your generator implemented. By the end of the week, even if your visuals are crude, the majority of your generator's functionality should be done.

Put all your code in your forked repository.

Submission: Add a new section to your README titled: Milestone #1, which should include
- written description of progress on your project goals. If you haven't hit all your goals, what's giving you trouble?

I had issues running some of the libraries that I was interested in on my computer, since it's an M1 mac (oof). The tidal cycles community was a great resource, after posting a help me post, the developer of the library helped me install tidal. I can now use tidal for the music generation portion of the project. 

Something that I'm still working on is getting a graphics library. I did find this cool graphics library called [veda](https://veda.gl/), which is build on top of glsl. I was able to get it up and running on my machine, but I won't be able to tie in any audio input into the graphics generator because of audio currently [doesn't work on mac m1's](https://github.com/fand/veda/issues/253). I also tried using pd+gem, but I experienced [some more issues](https://www.reddit.com/r/puredata/comments/yq36kc/gem_on_a_mac_with_m1_chip/) with my processor (I'm sensing a pattern here).

For now, I have just been using hydra in browser with the audio playing on the speakers, since hydra's audio source is the microphone. I might be able to use some OSC control to get around this if time permits.


- Examples of your generators output so far

...pending...

We'll check your repository for updates. No need to create a new pull request.
## Milestone 3: Implementation part 2 (due 11/28)
We're over halfway there! This week should be about fixing bugs and extending the core of your generator. Make sure by the end of this week _your generator works and is feature complete._ Any core engine features that don't make it in this week should be cut! Don't worry if you haven't managed to exactly hit your goals. We're more interested in seeing proof of your development effort than knowing your planned everything perfectly. 

Put all your code in your forked repository.

Submission: Add a new section to your README titled: Milestone #3, which should include
- **written description of progress on your project goals. If you haven't hit all your goals, what did you have to cut and why?** 

> I have finally found a devloop. I will be using [gibber](https://github.com/gibber-cc/gibberwocky) for my audiovisuals demo.
> 
> progress: 
>  - a minute of visuals
>  - an understanding of how to map fft to visuals
>  - osc exploration
>  - gibber/ scripting intro
>  - a working devloop (omg so happy)
>    - also, when i thought i wasn't making progress getting lost in tidal/hydra/veda/threejs documentaton, all of those examples still applied in the end because gibber has tidal and hydra support. also, it's in node/js which is nice since it's a nice recap of cis350.
> 
> goals: 
>  - more exploration with fft
>  - sequencing visuals
>  - loading samples
>  - running a local webserver to access local files
>    - maybe keyboard/midi if time permitting



- **Detailed output from your generator, images, video, etc.
We'll check your repository for updates. No need to create a new pull request.**

> here are some more clips of my first vj algojam
> 
> lines and waves
> [![Image from Gyazo](https://i.gyazo.com/e1cfeb201119d643f0815baf85d5dccf.gif)](https://gyazo.com/e1cfeb201119d643f0815baf85d5dccf)
> 
> bring in the square
> 
> [![Image from Gyazo](https://i.gyazo.com/98c1ce5fa0f9b843037f31961e23e39c.gif)](https://gyazo.com/98c1ce5fa0f9b843037f31961e23e39c)
>
> 
> jam with the cam
> 
> [![Image from Gyazo](https://i.gyazo.com/bf2527aecfa51dc404528de65f8d23c4.gif)](https://gyazo.com/bf2527aecfa51dc404528de65f8d23c4)





Come to class on the due date with a WORKING COPY of your project. We'll be spending time in class critiquing and reviewing your work so far.

## Final submission (due 12/5)
Time to polish! Spen this last week of your project using your generator to produce beautiful output. Add textures, tune parameters, play with colors, play with camera animation. Take the feedback from class critques and use it to take your project to the next level.

Submission:
- Push all your code / files to your repository
- Come to class ready to present your finished project
- Update your README with two sections 
  - final results with images and a live demo if possible
  - post mortem: how did your project go overall? Did you accomplish your goals? Did you have to pivot?

## Topic Suggestions

### Create a generator in Houdini

### A CLASSIC 4K DEMO
- In the spirit of the demo scene, create an animation that fits into a 4k executable that runs in real-time. Feel free to take inspiration from the many existing demos. Focus on efficiency and elegance in your implementation.
- Example: 
  - [cdak by Quite & orange](https://www.youtube.com/watch?v=RCh3Q08HMfs&list=PLA5E2FF8E143DA58C)

### A RE-IMPLEMENTATION
- Take an academic paper or other pre-existing project and implement it, or a portion of it.
- Examples:
  - [2D Wavefunction Collapse Pokémon Town](https://gurtd.github.io/566-final-project/)
  - [3D Wavefunction Collapse Dungeon Generator](https://github.com/whaoran0718/3dDungeonGeneration)
  - [Reaction Diffusion](https://github.com/charlesliwang/Reaction-Diffusion)
  - [WebGL Erosion](https://github.com/LanLou123/Webgl-Erosion)
  - [Particle Waterfall](https://github.com/chloele33/particle-waterfall)
  - [Voxelized Bread](https://github.com/ChiantiYZY/566-final)

### A FORGERY
Taking inspiration from a particular natural phenomenon or distinctive set of visuals, implement a detailed, procedural recreation of that aesthetic. This includes modeling, texturing and object placement within your scene. Does not need to be real-time. Focus on detail and visual accuracy in your implementation.
- Examples:
  - [The Shrines](https://github.com/byumjin/The-Shrines)
  - [Watercolor Shader](https://github.com/gracelgilbert/watercolor-stylization)
  - [Sunset Beach](https://github.com/HanmingZhang/homework-final)
  - [Sky Whales](https://github.com/WanruZhao/CIS566FinalProject)
  - [Snail](https://www.shadertoy.com/view/ld3Gz2)
  - [Journey](https://www.shadertoy.com/view/ldlcRf)
  - [Big Hero 6 Wormhole](https://2.bp.blogspot.com/-R-6AN2cWjwg/VTyIzIQSQfI/AAAAAAAABLA/GC0yzzz4wHw/s1600/big-hero-6-disneyscreencaps.com-10092.jpg)

### A GAME LEVEL
- Like generations of game makers before us, create a game which generates an navigable environment (eg. a roguelike dungeon, platforms) and some sort of goal or conflict (eg. enemy agents to avoid or items to collect). Aim to create an experience that will challenge players and vary noticeably in different playthroughs, whether that means procedural dungeon generation, careful resource management or an interesting AI model. Focus on designing a system that is capable of generating complex challenges and goals.
- Examples:
  - [Rhythm-based Mario Platformer](https://github.com/sgalban/platformer-gen-2D)
  - [Pokémon Ice Puzzle Generator](https://github.com/jwang5675/Ice-Puzzle-Generator)
  - [Abstract Exploratory Game](https://github.com/MauKMu/procedural-final-project)
  - [Tiny Wings](https://github.com/irovira/TinyWings)
  - Spore
  - Dwarf Fortress
  - Minecraft
  - Rogue

### AN ANIMATED ENVIRONMENT / MUSIC VISUALIZER
- Create an environment full of interactive procedural animation. The goal of this project is to create an environment that feels responsive and alive. Whether or not animations are musically-driven, sound should be an important component. Focus on user interactions, motion design and experimental interfaces.
- Examples:
  - [The Darkside](https://github.com/morganherrmann/thedarkside)
  - [Music Visualizer](https://yuruwang.github.io/MusicVisualizer/)
  - [Abstract Mesh Animation](https://github.com/mgriley/cis566_finalproj)
  - [Panoramical](https://www.youtube.com/watch?v=gBTTMNFXHTk)
  - [Bound](https://www.youtube.com/watch?v=aE37l6RvF-c)

### YOUR OWN PROPOSAL
- You are of course welcome to propose your own topic . Regardless of what you choose, you and your team must research your topic and relevant techniques and come up with a detailed plan of execution. You will meet with some subset of the procedural staff before starting implementation for approval.
