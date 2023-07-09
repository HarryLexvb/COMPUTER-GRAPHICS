# COMPUTER-GRAPHICS
This repository contains the work done during the course on computer graphics using OpenGl/GLFW in c++.

## Final Project: Cube rubik with solver and animation 

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
  
![solver](https://github.com/HarryLexvb/COMPUTER-GRAPHICS/assets/74415056/6717f7f2-abc9-450f-bcd2-5a3663bdcdbb)

- Snake animation 

![animation1](https://github.com/HarryLexvb/COMPUTER-GRAPHICS/assets/74415056/bce24576-39f5-42b5-8102-2e4da07911c2)

- Expansion animation

![animation3](https://github.com/HarryLexvb/COMPUTER-GRAPHICS/assets/74415056/9ad55f36-6b08-4001-9c23-8a276b687f80)

## Warning

This project has been implemented using visual studio code in its portable version in addition to using windows as operating system. It is also important to note that visual studio code portable is being run from a usb where I store the necessary dependencies, the c++ compiler and the project. 
