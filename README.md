Maze project
Background Context
The goal of this project is to create a game in 3D using raycasting !

Requirements
General
All your files will be compiled on Ubuntu 14.04 LTS, using gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4
We will use the gcc flags -Wall -Werror -Wextra and -pedantic
All your functions must be commented
Your functions should be maximum 40 lines long (one statement per line)
Your functions should be maximum 80 columns long
No more than 5 functions per file
Betty
Your entire repository will be checked using Betty
Don’t push any object files .o or temporary files *~, or any unused source file if you don’t want to lose points !
It is advised to always keep a clear organisation in your repository. For example, store all your sources in a src directory, and all your headers in a inc, headers or dependencies folder
More Info
Tips and links
SDL2 - Get started.pdf
SDL2 tutorials
Be careful with tutorials/help online: We are using SDL2, and not SDL-1.2 !
RAYCASTING !!!
Alternative Raycasting Tutorial
Important
Don’t forget to install SDL2 SDL2 tutorials
There are no forbidden functions for this project. You are allowed to use any system call and/or standard library function.
You are allowed to use all the functions provided by SDL2

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
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```

## Flowchart
![The Maze Flow Chart](https://i.imgur.com/t0MxNni.png)
