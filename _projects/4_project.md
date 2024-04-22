---
layout: page
title: Web Build SDL2 Game via Emscripten
description: EECS 498 Customized Feature Milestone
img: assets/img/ShowImage4GEA.png
importance: 1
category: EECS498
related_publications:
youtubeId: O1AiErMVshw?si=nPu2Q8MWH_zIR4N0
---

EECS498-GEA Final project finished by Jin Pan, advised by prof. Austin Yarger

My custom feature involves using Emscripten as the sole compiler toolchain to convert our C++ game engine into Web Assembly. This is significant because it streamlines the process for developers and enthusiasts who wish to explore or utilize our game engine. Typically, setting up a game engine involves extensive configuration, including the tedious tasks of managing header files and linking libraries. By compiling the engine into Web Assembly, we eliminate these barriers, enabling users to run the engine directly in their web browsers. This drastically reduces setup time and makes our technology accessible to a wider audience, enhancing user engagement and fostering a community of contributors.

This past week, I successfully integrated the Emscripten library into our project, which involved refactoring the main file and rewriting the makefile to support Web Assembly compilation. The result is both a functional local server and a github page deployment that serves as a proof of concept for web-based application of our game engine. Looking ahead to next week, my focus will be on two main enhancements. First, I plan to incorporate the web build of our game engine into my professional portfolio, which involves designing a user-friendly HTML template to improve the interface and user interaction. Second, to cater to gaming enthusiasts like myself who prefer physical controllers, I will try implementing joystick support. This addition is aimed at expanding the functionality of our engine and providing a more immersive experience for users.

**Technology utilized:** *Lua*, *C++*, *glm*, *Box2D*, *LuaBridge*, *SDL2*, etc..

**Specific features:**

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
    {% include youtubePlayer.html id=page.youtubeId %}
    </div>
</div>
<div class="caption">
    We also have the YouTube video for explaining how to use emscripten to web build our Game Engine to Web Build.
</div>




