# Entry 5
##### 4/8/24

## Context
In this **blog**, I will be explaining about my tool, *A-Frame*, and explain how I tinkered with **A-Frame** and how I learned it.
## Content/What I learned
When I first decided to choose **A-Frame**, I decided to first look at their [website](https://aframe.io/docs/1.5.0/introduction/). I read the basic introduction from the version 1.5.0 intro documen, which explains what is A-Frame. The doc says "A-Frame was developed to be an easy yet powerful way to develop VR content. As an independent open source project, A-Frame has grown to be one of the largest VR communities." Which describes some of A-Frame's uses.

#### TimeLine
In the beginning of March, I started my learning log.* On **youtube** I searched **A-Frame tutorials** and I found an interesting [video](https://www.youtube.com/watch?v=p3mNNZ356Ko) where I learned a lot of things and saw some stuff I know. In the beginning, the person has rotation and scale which I knew about, but for the numbers I am guessing that there are three for height, width, and length. They used color, primitives like boxes, and putting images in the website. Then I started to tinker on [Jsbin](https://jsbin.com/diyunidaco/edit?html,output), I looked at the video and wrote some code down throughout the video, but it didn't work on **Jsbin**. I think it is because the video was create on version 0.7.0 on A-Frame and now it is version 1.5.0 so stuff has changed, or because the images are needed to make the code function.

A week later, I learned more about A-Frame by reading from their document. I read the document about [3d models](https://aframe.io/docs/1.5.0/introduction/models.html) and [entities](https://aframe.io/docs/1.5.0/core/entity.html#example). I learned a lot from reading the *3D model doc*. I learned that I can create, find, and animate 3d models. And the document gives a list of places and programs on where to find 3d models and how to create them. I know that I can change an entitie's position, rotation, and scale. And that we can give it components, the components listed are geometry, material, and light components.

In the middle of March, I continued to learned more about my tool. On their website, I *read and tinkered* the code and text on how to build a basic scene. I went along the document, reading and putting the code in [Jsbin](https://jsbin.com/becobeqico/edit?html,output). Then I added some entites, changed the background color, changed the floor texture, and created a floor. At one point when creating the background, the background color was gradient with green and white. And during that learning log I learned how to start to animate the primitives. In [Jsbin](https://aframe.io/docs/1.5.0/guides/building-a-basic-scene.html), I tinkered on the positions of the primitives and where it gets to move. I made the box move in the x, y, and z planes. Which means I can make them go up and down, left or right, and backwards and forwards. And I can change the distance of the movement and how long it takes to get there and go back. dur:1000 is 1 second.

At the end of March, I reread the document on animation and I followed along on Jsbin. In the same [Jsbin](https://jsbin.com/becobeqico/edit?html,output) with the basic scene that I was tinkering with, I added more code to it. An example is
```
<a-entity rotation="0 0 0" animation="property: rotation; to: 0 360 0; loop: true; dur: 10000">
    <a-sphere position="5 0 0" easeOutCirc color="mediumseagreen"
    animation__mouseenter="property: components.material.material.color; type: color; to: blue; startEvents: mouseenter; dur: 500";
    animation__mouseleave="property: components.material.material.color; type: color; to: darkorange; startEvents: mouseleave; dur: 500";>
    ></a-sphere>
</a-entity>
```
I learned material opacity, which I think was suppose to make the primitive more or less transparent from my experience with youtube and messing with the text opacity. But then I read the thing and it said about properties and animate an arbitrary object. And I learned about other properties like to, dir, dur, delay, from, property, loop, and more. And I also learned that  I can put multiple animations on an entity, I just need to put two underscores "__" in the naming. Then I read about Easing, and I think I remember last time when we did something for a project and there were five groups, actually four since no one did geometry but there was easing in the animation groups slides. Also I put the animation where when the mouse hovers over the entity, it changes color from red to blue.

My last two learning logs I finished learning most of **A-Frame**. First I tinkered/tested the code that messes with the light in the entities. And after putting the code in *Jsbin*, the entities look shiny because of the light reflecting off of the shapes. From the document, I read that I could put some text in the scene. And that I can change the size, position, font, and more of it. I also put
```
<a-scene stats></a-scene>
```
in Jsbin, and it actally put the statistics. It tells you how much frames to takes, how long it takes for it to load, how many entities are in the scene, and more. Later I deleted it from the code because it was blocking a ton of the screen.

The week after, I learned some more new components and primitives from A-Frame, such as render, pool, and cubemap. The document says that pool is reusing entities that are already there without creating or destorying more. I learned and tinkered about half of the components. And I saw a primitive called a video-sphere. And it says that it plays 360 degree videos in the background of the scene.

## Skills
### Problem decomposition
Problem decomposition is a skill I learned during this blog. Because this blog is huge, so I broke it down and thought to myself what should I do in this amount of time and imaging what I am trying to accomplish.

### Growth Mindset
I continued to have the skill of Growth Mindset because part of me wants to be lazy, but I persevered and finished this blog.
[Previous](entry04.md) | [Next](entry06.md)
[Home](../README.md)
