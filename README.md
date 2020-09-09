# Tetris-game
This is an implementation of Tetris game with the C language using SDL library.

# Overview
![tetris](https://user-images.githubusercontent.com/24523745/92504206-3c0fae00-f1fa-11ea-9295-0c5b365155fd.png)

# Compiling & running the game 
Clone the repository and make sure that game files (.c and .h files) and the files which are in Blocks directory are in the same folder.

To compile the game, run the following command:

``` gcc -o main.exe main.c functions.c `sdl-config --libs` -lSDL_image ```

To run the game: 

``` ./main.exe ```

# Requirements
- SDL1.2
- SDL image 1.2
