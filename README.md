# Exchange UI
This repository is a fork of [ImPlot Demos](https://github.com/epezent/implot_demos) and it contains an implementation of an exchange user interface.

It is modified to work in UNIX systems.

## Requirements

- OpenGL
- C++17 compiler

**Note**: Minor changes to `CMakeLists.txt` may be required to support some compilers. If you make a fix, please submit a PR.

## Build Instructions
1. Clone this repository, [ImPlot](https://github.com/epezent/implot), and [ImGui](https://github.com/ocornut/imgui) into a parent directory (name doesn't matter):

```shell
mkdir root
cd root
git clone https://github.com/anouarac/exchange-ui.git
git clone https://github.com/epezent/implot
git clone https://github.com/ocornut/imgui
```

- `root/`
    - `imgui/`
    - `implot/`
    - `exchange-ui/`
2. Build with CMake, e.g.:
```shell
cd exchange-ui
mkdir build
cd build
cmake ..
cmake --build . --config Release
```
