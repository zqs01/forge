## Forge - High Performance Visualizations
| Platform | Linux x86 | Linux aarch64 | Windows | OSX |
|:--------:|:---------:|:-------------:|:-------:|:---:|
| Status   | [![Build Status](https://travis-ci.org/arrayfire/forge.svg?branch=v1.0)](https://travis-ci.org/arrayfire/forge) | `Unknown` | [![Build Status](https://ci.appveyor.com/api/projects/status/github/arrayfire/forge?branch=v1.0&svg=true)](https://ci.appveyor.com/project/9prady9/forge-jwb4e) | [![Build Status](https://travis-ci.org/arrayfire/forge.svg?branch=v1.0)](https://travis-ci.org/arrayfire/forge) |

[Join the slack chat channel](https://join.slack.com/t/arrayfire-org/shared_invite/enQtMjI4MjIzMDMzMTczLWM4ODIyZjA3YmY3NWEwMjk2N2Q0YTQyNGMwZmU4ZjkxNGU0MjYzYmUzYTg3ZTM0MDQxOTE2OTJjNGVkOGEwN2M)

An OpenGL interop library that can be used with ArrayFire or any other application using CUDA or OpenCL compute backend. The goal of **Forge** is to provide high performance OpenGL visualizations for C/C++ applications that use CUDA/OpenCL. Forge uses OpenGL >=3.3 forward compatible contexts, so please make sure you have capable hardware before trying it out.

### Documentation

You can find the most recent and updated documentation [here](http://arrayfire.org/forge/index.htm).

### Dependencies

- [GLFW](http://www.glfw.org/) or [SDL2](https://www.libsdl.org/)
- [freetype](http://www.freetype.org/)
- [glm](https://glm.g-truc.net) - not a runtime dependency
- [boost](https://www.boost.org/) - not a runtime dependency.
- [FreeImage](http://freeimage.sourceforge.net/) (optional).
- [fontconfig](http://www.freedesktop.org/wiki/Software/fontconfig/) on Linux and OSX.

**Linux/Unix**: Dependencies should be available via respective package managers.
**Windows**: We recommend [vcpkg](https://github.com/Microsoft/vcpkg).

### Sample Images
|     |     |
|-----|-----|
| <img src="./docs/images/image.png" width=150 height=100>Image</img> | <img src="./docs/images/plot.png" width=150 height=100>2D Plot</img>  |
| <img src="./docs/images/plot31.png" width=150 height=100>3d Plot</img> | <img src="./docs/images/plot32.png" width=150 height=100>Rotated 3d Plot</img> |
| <img src="./docs/images/hist.png" width=150 height=100>histogram</img> | <img src="./docs/images/surface.png" width=150 height=100>Surface</img> |
