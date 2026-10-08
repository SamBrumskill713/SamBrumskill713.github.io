---
title: Data Oriented Design Dissertation
publishDate: 2026-05-27 15:00:00
img: /assets/DOD-dissertation-screenshot.png
img_alt: A Screenshot from DOD Dissertation
description: |
  A Performance comparison between Data Oriented Design and Object Oriented Programming (TBD).
tags:
  - C++
  - Computer Architecture
  - Data Oriented Design
  - Object Oriented Programming
  - Memory Layout
---
## Data Oriented Design Dissertation
### Links:
<iframe width="560" height="315" src="https://www.youtube.com/embed/b8FbDDmuNlA?si=4JLp3zxgnowQW7jZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


<a href="https://GitHub.com/SamBrumskill713/Data-Orienated-Design-Dissertation-CSC8599">GitHub Repo</a>

### What I did
For my dissertation, I decided to do a performance comparison between Data-Oriented Design and Object Oriented Design. I did this by converting the framework made in the game technologies coursework from Object-Oriented to Data-Oriented. The main reason for this was to see how game performance could be affected by a change in programming paradigm that focuses on efficient use of cache hierarchy and cache lines. The results showed that Data-Oriented Design was much more performant when compared to Object-Oriented Programming.
### What I learned
Data-Oriented Design (DOD) showed much greater performance because of efficient use of cache Hierarchy and cache lines. This is achieved due to a greater focus on memory layout and memory access. In Object-Oriented Programming (OOP), data is essentially hidden and can become hard to access. This is further compounded upon by inheritance and polymorphism which cause scattered memory layout meaning that cache lines cannot be utilised as efficiently.

By focusing on memory layout and memory access, DOD can efficiently use cache hierarchy and cache lines by not hiding data and not making data a part of the problem domain and instead focus on how data is transformed throughout the program. This dissertation also showed that Structure of Arrays (SoA) performed slightly better than Array of Structures (AoS). However, in another test that artificially filled AoS and SoA with garbage data, SoA performed much better since that data isn’t accessed since its contained in a separate array whereas that data is included in the record in the AoS implementation.    
### Future work
The main drawback of the dissertation is that multithreading was not explored, this could also further demonstrate how memory layout affects performance in a concurrent setting. A reduction of boolean values could also show the benefits of DOD when compared to OOP since there would be no padding in memory alignment. Other game systems such as AI and Networking could have also been explored in showing the difference between DOD and OOP since the dissertation mainly covers the physics and, to a lesser extent, the rendering parts of the engine.