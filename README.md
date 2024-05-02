### Requirements:

- [CMake](https://cmake.org/download/)
- [ninja](https://github.com/ninja-build/ninja)
- Up-to-date [C/C++](https://nuwen.net/mingw.html) compiler

**NOTE:** I recommend to use [scoop](https://scoop.sh/) to install them, if you're on windows.

### Run:

1. Create a build directory

```sh
mkdir build
cd build
```

2. Use ninja generator to build the project

```sh
cmake -G "Ninja" ..
cmake --build .
```
