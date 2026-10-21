# C++ Tetris

An (almost) classic implementation of Tetris built in C++ using **ncurses** for a smooth terminal user interface. 

---

## Features

* Classic Tetris gameplay mechanics inside the terminal.
* Added a Custom 'gravity-mode', inspired by the hit PS4 game: Tricky Towers
* Built with modern **C++17**.
* Powered by **ncurses**.
* Built using **CMake**.

---

## Prerequisites

Before compiling the project, make sure you have:
* A modern C++ compiler supporting **C++17** (like GCC 13).
* **CMake** (version 3.15 or higher).
* The **ncurses** development library.

### On Ubuntu / Debian:
```bash
sudo apt update
sudo apt install build-essential cmake libncurses-dev
```


### On macOS:
```bash
brew install cmake ncurses
```


### Building from Source

```bash
# 1. Clone the repository
git clone [https://github.com/Reculum/Cpp-Tetris.git](https://github.com/Reculum/Cpp-Tetris.git)

cd Cpp-Tetris

# 2. Configure the project using CMake (creates a 'build' folder)
cmake -B build -S .

# 3. Compile the executable
cmake --build build
```

### Running Tetris (on Linux/macOS)

```bash

touch build/punteggi.txt
./build/Tetris


