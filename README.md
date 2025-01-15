# Custom-Renderer
 
# Computer Graphics - UCSanDiegoX: Homework 1: Camera Transformations

This repository contains the solution for Homework 1 from the **UCSanDiegoX: Computer Graphics** course on edX. The assignment focuses on implementing transformations and camera movements in 3D space, using basic math and vector operations.

## About the Course

The **Computer Graphics** course from UCSanDiegoX is an introductory course that covers fundamental concepts of computer graphics, including 3D scene creation, camera movement, real-time rendering, and ray tracing. This specific assignment emphasizes transformations such as camera rotations and vector manipulations.

### Key Learning Outcomes:
- Understanding of camera transformations in 3D graphics.
- Implementing rotations around an arbitrary axis in space.
- Applying basic linear algebra to manipulate camera view matrices.

## Assignment Overview

In this assignment, the goal was to implement a function that rotates the camera in 3D space. The code below demonstrates the correct transformation of the camera's **eye** and **up** vectors to simulate the camera's rotation in space, preserving the relationship between the "eye" and the "up" directions.

### The Problem
You are tasked with rotating the camera **up** vector by a specified number of degrees, around an axis perpendicular to the current **eye** and **up** vectors.

### The Solution
The solution uses Rodrigues' rotation formula to perform the camera rotation, ensuring that both the **eye** and **up** vectors are properly rotated while maintaining the correct orientation in 3D space.
