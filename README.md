Maze project

The goal of this project is to create a game in 3D using raycasting !


# The Maze

The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!

The Maze was written was written in C ussing SDL2 library. Deveploment was performed using Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4

### About SDL2 

Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

## Instalation 
```sh
$ git clone https://https://github.com/Evans-Gash/The-Maze.git
```
## Usage 
* Execute ./maze or type make run 
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)

## Compilation
```sh
gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```

## Flowchart
![The Maze Flow Chart](https://i.imgur.com/t0MxNni.png)

## Simply-The-Maze-*DEMO*
(https://drive.google.com/file/d/1pm-yWnOUFN0D1WwLSZGtPmY5u_oTd_Jf/view?usp=sharing)

## The Maze Report *Status Update*
https://docs.google.com/document/d/1QoruEySWPLYDsTCxkPL_9bHkufDM8qYJrzDbLi2WBWQ/edit?usp=sharing

## The Maze Presentation Pitch-deck *Slides*
https://slidesgo.com/editor/share/9ac83e2c-c0dd-42f3-8574-26589e3227ac#rs=link

## Portfolio Project Blog post *Unveiling the Depths: Crafting a Maze 3D with Raycasting*
https://evansgashmugambi.blogspot.com/2023/12/unveiling-depths-crafting-maze-3d-with.html
