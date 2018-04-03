# CS184 Final Project Proposal: Creating a Demo with Custom Cel Shading

###### Nathan Yuchi, 26576388
###### Kyan Russell, 25124970
###### Henry Sun, 3031840488

## Summary: 

We want to create a cel shader to render stylized scenes. Cel shading historically has been used to achieve a very flat, "cartoonish" look. Many successful video games, such as *The Legend Of Zelda: The Wind Waker*,  use this shading method.

![alt text](https://forums.unrealengine.com/filedata/fetch?id=1076570&d=1507083411 "Logo Title Text 1")

## Problem Description

![alt text](https://upload.wikimedia.org/wikipedia/commons/8/8a/Celshading_teapot_large.png "Logo Title Text 1")

- *Here you should provide the context for your idea. Describe the problem that you are trying to solve, why it is important, where it is challenging. Give us a general idea on how you are going to solve it.*

We want to experiment with the various visual effects one can achieve with cel shading. There are many stylistic decisions to be made, such as how realistic one wants the effect to be. For example, *DRAGON BALL FighterZ* and *The Legend of Zelda: Breath of the Wild* both feature rather realistic scenes using cel shading.

![alt text](https://uproxx.files.wordpress.com/2018/01/dragon-ball-fighterz.jpg?quality=95 "Logo Title Text 1")

The difference between cel shading and a more realistic shader can be seen here.

![alt text](https://i.kinja-img.com/gawker-media/image/upload/s--R-_JyTsw--/c_scale,fl_progressive,q_80,w_800/unrit4bhz2pejh2fvkzv.jpg "Logo Title Text 1")

Hand-drawn effects can also be achieved, such as in the game *Ōkami*.

![alt text](okami.jpg "Logo Title Text 1")






## Goals and Deliverables

*This is the most important part of your proposal. You should carefully think through what you are trying to accomplish, what results you are going for, and why you think you can accomplish those goals. For example:*

- *Since this is a graphics class you will likely define the kind of images you will create (e.g. including a photo of a new lighting effect you will simulate).*

- *If you are working on an interactive system, describe what demo you will create.*

- *Define how you will measure the quality / performance of your system (e.g. graphs showing speedup, or quantifying accuracy). It may not be possible to define precise target metrics at this time, but we encourage you to try.*

- *What questions do you plan to answer with your analysis?*

*You should break this section into two parts: (1) what you plan to deliver, and (2) what you hope to deliver. In (1), describe what you believe you must accomplish to have a successful project and achieve the grade you expect (i.e. your baseline plan -- planning for some unexpected problems would make sense). In (2), describe what you hope to achieve if things go well and you get ahead of schedule (your aspirational plan).*

*(1) What you plan to deliver:*

A shader that creates non-realistic renderings, specifically in the cel-shading.  We would like to extend it to non-realistic

*(2) What you hope to deliver:*

A GUI that allows the user to control parameters regarding the shading to show different styles of non-realistic shading depending on the parameters used.

Expand non-realistic rendering to the entiire pipeline of rendering instead of just shading.  E.g. creating 2d key frames, drawn in with the whole color, detail, texture, style, etc., making 3-d models and scenes with maya/blendr, and extrapolate the data from the keyframe that matches the models, to get the texture, artistic brush style, etc, and use that to interpolate in-between motion for animation.

## Schedule

- *In this section you should organize and plan the tasks and subtasks that your team will execute. Since presentations are ~4 weeks from the due-date of the proposal, you should include a set of tasks for every week.*

T-4 weeks - Solidify topic and distribute tasks.  Attend sections and office hours for guidance

t-3 - code code code

t-2 Finish up coding, begin creating presentation visuals and renderings.  Work out any bug fixes

T-1 - Wrap up presentation, finish rendering images, finish recording necessary videos, begin writing notes/scripts for presentation

t-0 - PRESENT!

## Resources

- *List what resources, e.g. books, papers and/or online resources that are references for your project. List the computing platform, hardware and software resources that you will use for your project. You have a wide latitude here to use what you have access to, but be aware that you will have to support and trouble-shoot on your platform yourselves. If you are starting from an existing piece of code or system, describe and provide a pointer to it here.*

<http://rbwhitaker.wikidot.com/toon-shader>

Possible references for a broader topic.  As the topic changes and begins to solidfy, we will choose certain parts of the following resurces to use.

- The Algorithms and Principles of Non-photorealistic Graphics
<https://drive.google.com/file/d/1S8omOyieH1yNCcMTwPfCwpM3v6M3PIo9/view>

- A Survey of Surface-Based Illustrative Rendering for Visualization
<https://drive.google.com/file/d/18ZWCQ0O8IKPiCzrJ8-qJ3cligLZVN6LY/view>

- None-Photorealistic Computer Graphics
<https://drive.google.com/file/d/1ZScMnYh_l1hHiXr2ql4tkhmI8NHO5vs2/view>

- Real Time Nonphotorealistic Rendering
<https://drive.google.com/file/d/1XOZbQ91OK0Dzu_0WIZ3UW5AV2nE4MKjX/view>




