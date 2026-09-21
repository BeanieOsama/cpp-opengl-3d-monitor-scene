# Implementation Overview

This project was completed using an instructor-provided OpenGL framework for SNHU's CS 330 Computational Graphics and Visualization course.

My work focused on designing and implementing the final 3D monitor scene within that framework.

## My Contributions

### Scene Composition

I constructed the monitor from multiple primitive meshes rather than using a single pre-built model.

The scene includes:

- Monitor body
- Display screen
- Rear connector
- Monitor stand
- Monitor neck
- Monitor base
- Desktop surface

Each component was individually positioned, scaled, and rotated before being combined into the final scene.

## Materials

I configured separate material properties for:

- Wood
- Plastic
- Metal

These materials use different ambient, diffuse, specular, and shininess values to create different visual responses to lighting.

## Lighting

I configured multiple light sources for the scene.

The primary light provides general illumination for the monitor and desktop, while a secondary warmer light adds variation to the scene.

I also disabled lighting temporarily when rendering the monitor display so the screen texture remained visible instead of becoming overly dark.

## Texture Mapping

The scene uses different textures for:

- Wooden desktop
- Metal monitor components
- Plastic monitor body
- Monitor display

I also adjusted UV scaling depending on the object and texture.

## Transformations

Each object uses combinations of:

- Translation
- Rotation
- Scaling

This allowed basic geometric primitives to be combined into a more complex recognizable object.

## Graphics Concepts Applied

Through this project, I worked with:

- Model transformations
- 3D coordinate systems
- Perspective rendering
- Texture mapping
- UV coordinates
- Material properties
- Ambient lighting
- Diffuse lighting
- Specular lighting
- Multiple light sources
- Shader-controlled rendering
- Composite 3D objects
- C++ debugging

## Framework Attribution

The underlying OpenGL framework and supporting utilities were provided as part of the SNHU CS 330 course.

This repository focuses on the scene design, configuration, graphics concepts, and implementation work I completed using that framework.
