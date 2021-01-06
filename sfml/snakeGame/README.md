# snake game

**requirements**

- [SFML 2.4.1](https://www.sfml-dev.org/)

**linux**

```bash
sudo apt-get install libsfml-dev
```

**windows**

- Add the `</path/to/sfml/>/include` to your c++ include path
- Then add </path/to/sfml/>/lib to the linker extra library path

**MS build**

- Visual Studio 15 or above
- VC++ 15 or above

**linux**

- g++ 4.8 or above
- GNU make

## building the game

MS build

- Download the source code
- import into visual studio
- build according to your need (x64 or x86 or whatever)

```
Don't forget to link the sfml libraries - graphics, window and system.
put the following files in linker input:
sfml-system-d.lib, sfml-window-d.lib, sfml-graphics-d.lib and GameMenu.lib
```

- Copy the sfml dlls (window, graphics and system) along with the executable
- Then Run and enjoy

## using makefile

- Download the source code
- go to directory game

```bash
cd snakeGame
```

- run make

```bash
make
```

- the exectable `bin/game` should apear. The directory will be created if doesn't exist.

## screenshot

![snakeGame](https://github.com/bellshade/cppSourceCode/blob/main/sfml/snakeGame/menuSnakeGame.png?raw=true)
![snakeGame1(https://github.com/bellshade/cppSourceCode/blob/main/sfml/snakeGame/onSnakeGame.png?raw=true)
