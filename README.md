## C++ OpenGL 3D Monitor Scene

A 3D computer graphics project developed with C++, OpenGL, and GLM as part of my CS 330 Computational Graphics and Visualization coursework at Southern New Hampshire University.

This project uses an instructor-provided OpenGL framework as its foundation. My work focused on designing and implementing the final 3D scene, including object composition, transformations, textures, materials, lighting, camera behavior, and overall scene presentation.

## Project Overview

For this project, I created a 3D desktop monitor environment using multiple geometric primitives.

The monitor was constructed from several individual components rather than a single pre-built model. Each component was independently positioned, scaled, rotated, textured, and combined to create the final scene.

The completed environment includes:

- Monitor body
- Display screen
- Rear connector
- Monitor stand
- Monitor neck
- Monitor base
- Textured desktop surface

## Technologies

- C++
- OpenGL
- GLM
- GLSL
- Visual Studio
- Git and GitHub

## Features

- Real-time 3D rendering
- Object translation, rotation, and scaling
- Perspective projection
- Camera navigation
- Texture mapping
- UV texture scaling
- Multiple material types
- Multiple light sources
- Shader-based rendering
- Composite objects created from primitive meshes

## Graphics Concepts

## Project Screenshot

![Final 3D Monitor Scene](Graphics-screenshots/final-scene.png)

- 3D coordinate systems
- Vector and matrix mathematics
- Model transformations
- View and perspective transformations
- Texture mapping
- Material properties
- Ambient lighting
- Diffuse lighting
- Specular lighting
- Multiple light sources
- Shader-controlled rendering
- Debugging graphical and transformation issues

## Scene Design

The scene represents a desktop computer monitor positioned on a textured wooden surface.

I assembled the monitor from separate geometric components and configured different materials for wood, plastic, and metal surfaces.

The scene uses multiple light sources to create different lighting effects across the monitor and desktop.

The monitor display is rendered separately from the surrounding objects so the screen texture remains visible without becoming excessively dark from the scene lighting.

## Development Process

I built the scene incrementally by creating and adjusting individual components before combining them into the complete environment.

This made it easier to isolate and troubleshoot problems involving:

- Object positioning
- Scale
- Rotation
- Camera perspective
- Lighting
- Materials
- Texture placement

Working through these issues strengthened my understanding of debugging visual software and demonstrated how relatively small mathematical changes can significantly affect a rendered 3D environment.

## What I Learned

This project helped me apply C++ to graphical software rather than only console-based applications.

I gained practical experience with how transformations control objects in 3D space and how cameras, lighting, textures, materials, and shaders work together within a graphics pipeline.

The project also strengthened my interest in C++, real-time graphics programming, game development, and interactive software.

## Project Screenshot

The completed 3D scene will be shown here after the project screenshot is added to the repository.

## Attribution

This project was completed for Southern New Hampshire University's CS 330 Computational Graphics and Visualization course.

The original OpenGL framework and portions of the supporting graphics infrastructure were provided as course materials. My contributions focused on the design and implementation of the final 3D monitor scene, including object composition, transformations, materials, lighting, textures, camera configuration, and visual presentation.

Course-provided framework material is not redistributed in this portfolio repository. cpp-opengl-3d-monitor-scene
C++ and OpenGL 3D graphics project featuring transformations, textures, materials, lighting, and camera controls.
