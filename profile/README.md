# CS 4053/5053 Group Project

The group project of Caleb Guinn, Jose Saldivar, and William Wilson.

🚀 Cool technical graphics stuff! 🎨


# Useful Links

[Shadertoy](https://www.shadertoy.com/new) - Learn by doing. Write, compile, and run shaders in your browser. Learn GLSL (the shader language) and apply techniques from other resources without having to write all the Java+OpenGL boilerplate!

[docs.gl](https://docs.gl/) - Online, searchable, filterable (by OpenGL version) documentation for OpenGL functions.

[noclip.website](https://noclip.website/) - Explore levels from various video games in your brower. Includes a plethora of shader effects on display.

## Shader Introduction Videos

Here are several videos which introduce shaders in OpenGL. They are organized by duration from short to longform to make it easier to choose a video to watch based on your interest and the amount of time you have.

One approach I recommend would be to watch them in order from shortest to longest over several days. Don't worry about writing code or getting anything drawing at this point. On the first day, watch the shortest video and then spend some time thinking about the interesting effects you have seen in games and maybe do some searches for those different effects. On the second day, watch the second (and third, technically) videos (by The Cherno, less than 45 min) in order to see how shaders are written, compiled, and activated in OpenGL. Finally, buckle up and sit down on a Saturday morning with a cup of coffee and tackle the 3+ hours of the last video. 

This video gives a brief introduction to shaders; what they are and a couple of their uses.

* Short: [this](https://youtu.be/sXbdF4KjNOc) (< 10 min)

These two videos introduce the concept of shaders and coding in C/C++ with the OpenGL API to load, compile, and activate shader code and render some triangles.

* Medium [this](https://youtu.be/5W7JLgFCkwI) and [that](https://youtu.be/71BLZwRGUJE) (< 45 min).

A very long -but interesting and instructive!- video which shows examples of how shaders are used to achieve certain effects in games. Shows the implementation of shaders in the Unity game engine as opposed to "raw" OpenGL. 

* Long: [this](https://youtu.be/kfM-yu0iQBk) (< 4 hours)

Other videos (after learning about shaders):

* [OpenGL Crash Course (freeCodeCamp)](https://youtu.be/45MIykWJ-C4) - C/C++, OpenGL, and GLSL tutorial that starts from scratch and builds to rendering models loaded from files. A little fast paced and leaves out a lot of details. Would need to translate from C++ to Java (that should not be too difficult though).
* [How scrolling textures gave Super Mario Galaxy 2 its charm (Jasper)](https://youtu.be/8rCRsOLiO7k) - a discussion of how Nintendo uses creative techniques to add polish and charm to its games, specifically exploring texturing in Super Mario Galaxy 2.
* [How The Wind Waker Redefined Cel Shading](https://youtu.be/mnxs6CR6Zrk) - a video essay deconstruction of how cell shading works in The Legend of Zelda: The Wind Waker.
* [Why Did Link's Cel Shading Disappear?](https://youtu.be/By7qcgaqGI4) - a video essay exploring a bug in the The Legend of Zelda: Breath of the Wild leading to a decontruction of the game's shader pipeline.
* [Creating a Scene for my 3D Pixel Art Game](https://youtu.be/ERA7-I5nPAU) - process video showing how simple polyhedra can become an amazing scene when good shading effects are applied. 

## The Red Book

This book is tome which is useful for learning/reference on ***anything*** and ***everything*** about modern OpenGL. It might be a good idea to read chapters 1 - 4 start to finish and just reference other chapters depending on what kind of effects we want to implement.

*"Check the GroupMe or ask me for the link to the book."* - William

## Ray Tracing in One Weekend

A [C/C++ book series](https://raytracing.github.io/) which guides the reader through building a ray tracing renderer from scratch. It is a good book for learning some of the basic mathematics and physics models on which ray tracing is based. However, the book does not cover implementing ray tracing on modern GPUs and does not use OpenGL at all.