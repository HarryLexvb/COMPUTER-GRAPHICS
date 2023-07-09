# COMPUTER-GRAPHICS
This repository contains the work done during the course on computer graphics using OpenGl/GLFW in c++.

## Authors

* **Harold Alejandro Villanueva Borda** - *San Pablo Catholic University* 
* **Cledy Becerra Sipiran** - *San Pablo Catholic University* 
* **Massiel Oviedo Sivincha** - *San Pablo Catholic University*

## Requirements
The sample code for the `Rubik's Cube` needs CMake 3.20.0 or later.
This project also depends on 4 libraries:

* [GLFW](https://www.glfw.org/)
* [GLAD](https://github.com/Dav1dde/glad)
* [GLM](https://github.com/g-truc/glm)
* [FREEIMAGE](https://freeimage.sourceforge.io/)

## Solver
We use the Herbert Kociemba's two-phase algorithm for solving Rubik's Cube, you can found it in this [GitHub](https://github.com/muodov/kociemba)

## Instructions 📦

- With the following keys you will be able to unorder the cube 

| Key | Clockwise Movement |
| ------------- | ------------- |
| Q  | R |
| W  | L |
| E  | U |
| R  | D |
| T  | F |
| Y  | B |
| X  | Randon disolver |

- With the following keys you will be able to solve the cube

| Key | Description |
| ------------- | ------------- |
| Z  | Solve the unscrambled cube manually |
| C  | Solve the unsorted cube randomly  |

- For animation

| Key | Description |
| ------------- | ------------- |
| 1  | Perform 'Snake' animation |
| 2  | Perform the animation of breathing  |
| 3  | Perform animation 'Expansion'  |

- For the camera 

| Key | Description |
| ------------- | ------------- |
| UP | Zoom |
| DOWN | Zoom out |
| LEFT | Move left  |
| RIGHT | Move right  |
| MOUSE | Change camera position  |

## Demo 

- Solver and disolver
  
![1](https://github.com/HarryLexvb/COMPUTER-GRAPHICS/assets/74415056/b76c6084-33e9-43b9-9b7b-ca433ea2534b.mp4) 

