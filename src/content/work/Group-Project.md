---
title: Group Project
publishDate: 2025-11-15 00:00:00
img: /assets/GroupProject.png
img_alt: A screenshot from Group Project
description: |
  Group Project for Masters (75/100)
tags:
  - C++
  - CMake
  - Jolt
  - ENet
  - Networking
  - Data Driven Design
---
## Masters Group Project
### Links:
PS5 Build: </n>
<iframe width="600" height="400" src="https://www.youtube.com/embed/QGP9eVH0AKo" 
title="CSC8508 Group Project PS5 Build" frameborder="0" allow="accelerometer; autoplay; 
clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</n>
PC Build: </n>
<iframe width="600" height="400" src="https://www.youtube.com/embed/iOAtWiHzFY4" title="CSC8508 - VideoSinglePlayer Game" frameborder="0" allow="accelerometer; autoplay; clipboard-write;
encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</n>

### Our Group Project:
For our Group Project, we were tasked with creating a game from scratch building on the concepts we were taught in the previous courseworks. The main requirments were that the game had to be child friendly and be playable on a PS5. We decided to make a cross between Smash Bros and Quake. The core movement is inspired by quake movement but the main goal is to knock enemies and other players off the stage after getting thier damage percentage high enough.  

### What did I do?
For this project, I was the main network and tools programmer, while also contributing to gameplay programming and working on the initial engine programming team trying to have the game compile with Jolt, FMOD, and ImGui.
In this project we used the following libraries and middleware:
<ul>
	<li> OpenGL for rendering </li>
	<li> Jolt for physics </li>
	<li> FMOD for audio </li>
</ul>

The main tool I made was a data-driven level creator that loads levels and sets different values from a JSON file, this meant that the game didn't need to recompile every time we made a change to a stat or wanted to test a specific level or mechanic. I also created a moving platform and AoE for the game. I was the only network programmer on the team and was responsible for having an accurate representation of the game for online play, this was achieved by using the ENet library and establishing a server-client architecture similar to Quake 3. I was also on the engine programming team which saw us using CMake to have the different libraries link and compile. 
### What did I learn?

This project emphasised the importance of teamwork and communication between different teams and how to effectively utilise source control through GitHub. This also allowed me to develop my skills in tools programming and network programming when compared to the Game Technologies coursework thanks to the scope of the project being much larger. This also allowed me to develop my skills in CMake in the inital stages of the project.

Although the game was far from ideal, the engine and systems worked well and the game compiled on both PC and PS5.
