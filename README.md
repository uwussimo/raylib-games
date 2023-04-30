# Raylib Games: Floppy example

This is a simple implementation of the classic game Flappy Bird using the [raylib](https://www.raylib.com/) game development library. The game was developed by Ian Eito, Albert Martos, and Ramon Santamaria.

## Installation

To run the game, you will need to install raylib. Please refer to the [official installation guide](https://www.raylib.com/cheatsheet/cheatsheet.html#development-platforms-installation) for instructions on how to install raylib on your platform.

Once you have installed raylib, you can compile and run the game by typing the following command:

```
cd ./build
mingw32-make
./Game.exe
```

## How to Play

The goal of the game is to guide the floppy bird through a series of pipes without colliding with them. The bird automatically moves forward and the player can control the bird's altitude by pressing the spacebar. The game ends if the bird collides with a pipe or if the bird falls off the screen.

## Controls

- Press spacebar to make the bird fly higher
- Press 'P' to pause the game
- Press Enter to restart the game after a game over

## License

This game is licensed under an unmodified zlib/libpng license. Please see the `raylib.h` file for more information.
