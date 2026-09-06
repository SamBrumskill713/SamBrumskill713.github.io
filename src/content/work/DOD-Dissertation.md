---
title: Data Oriented Design Dissertation
publishDate: 2026-05-27 15:00:00
img: /assets/DOD-dissertation-screenshot.png
img_alt: A Screenshot from DOD Dissertation
description: |
  A Performance comparision between Data Oriented Design and Object Oriented Programming (TBD).
tags:
  - C++
  - Computer Architecture
  - Data Orientated Design
  - Object Oriented Programming
  - Memory Layout
---
## Data Oriented Design Dissertation
### Links:
<iframe width="560" height="315" src="https://www.youtube.com/embed/b8FbDDmuNlA?si=4JLp3zxgnowQW7jZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### What I did
For my dissertation, I decided to do a performance comparision between Data-Oriented Design and Object Oriented Design. I did this by converting the framework made in the game technologies coursework from Object-Oriented to Data-Oriented. The main reason for this was to see how game performance could be affected by a change in paradigm that focuses on efficent use of cache hierarchy and cache lines. The results showed that Data-Oriented Design was much more performant when compared to Object-Oriented Programming.
### What I learned
Data-Oriented Design (DOD) showed much greater performance because of efficent use of cache Hierarchy and cache lines. This is achieved due to a greater focus on memory layout and memory access. In Object-Oriented Programming (OOP), data is essentially hidden and can become hard to access. This is further compounded upon by inheritance and polymorphism which cause scattered memory layout meaning that cache lines can't be utilised efficently. 

By focusing on memory layout and memory access, DOD can efficently use cache hierarchy and cache lines by not hiding data and not making data apart of the problem domain and instead focus on how data is transformed throughout the program. This disseration also showed that Structure of Arrays (SOA) performed slightly better than Array of Structures (AOS). However, in another test that artificially filled AOS and SOA with garbage data, SOA performed much better since that data isn't accessed since its contained in a seperate array whereas that data is included in the record in the AOS implementation.    
### Future work
The main drawback of the dissertation is that multi-threading was not explored, this could also show how memory layout affects performance in a concurrent setting. A reduction of boolean values could also show the benefits of DOD when compared to OOP since there would be no padding in memory alignment. Other game systems such as AI and Networking could've also been explored in showing the difference between DOD and OOP since the disseration mainly covers the physics and, to a lesser extent, the rendering parts of the engine. 