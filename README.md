CS 330 Computational Graphics and Visualization

Project Overview

This repository contains my final CS 330 project, including the completed 3D scene ZIP folder and my Design Decisions document. For the project, I created a 3D desktop scene with a monitor, keyboard, notepad, coffee mug, and other objects arranged on a textured wooden desk. I constructed the objects from basic OpenGL meshes, applied textures and materials, added multiple light sources, and implemented camera controls with perspective and orthographic viewing modes.

How Do I Approach Designing Software?

This project helped me learn how to break a larger visual idea into smaller, manageable components. I started by studying the reference image and identifying the basic shapes that could represent each object. From there, I planned the scale, rotation, and position of each mesh before combining them into the full scene. I also learned that textures, lighting, and camera placement need to be considered as part of the design instead of being treated as separate finishing steps. In future projects, I can use this same approach by dividing requirements into smaller features, building them individually, and checking how they work together before moving forward.

How Do I Approach Developing Programs?

I developed the scene through repeated testing and adjustment. Each milestone added another part of the program, beginning with basic objects and transformations, followed by camera navigation, textures, materials, and lighting. I tested the program after making small changes so I could identify problems with object placement or rendering without having to troubleshoot the entire scene at once. My approach became more organized throughout the course because I learned to separate responsibilities such as texture loading, material definitions, lighting setup, camera input, and scene rendering. Iteration was especially important because small changes to coordinates, lighting intensity, and camera position could noticeably change the final result.

How Can Computer Science Help Me Reach My Goals?

Computational graphics gave me more experience with C++, OpenGL, debugging, coordinate systems, transformations, and user input. These skills can support future coursework involving software development, simulations, data visualization, or interactive applications. Professionally, this project strengthened my ability to translate a visual requirement into working code, test my decisions, and improve the result based on feedback. Even if I do not work directly in graphics, the problem-solving, modular design, and debugging skills I practiced can transfer to software development and cybersecurity work.

Repository Contents

3D Scene ZIP: Complete Visual Studio project, source code, supporting files, and executable

Design Decisions: Explanation of my development choices, camera controls, and program organization

README: Project overview and reflection on the design and development process

Scene Controls

W / S: Move forward and backward

A / D: Move left and right

Q / E: Move up and down

Mouse: Change the camera orientation

Mouse wheel: Adjust movement speed

P: Switch to perspective projection

O: Switch to orthographic projection
