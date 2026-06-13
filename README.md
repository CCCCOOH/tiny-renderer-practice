# tiny-renderer-practice

A software renderer built from scratch, following the classic [tinyrenderer](https://github.com/ssloy/tinyrenderer) course. Implements the full graphics pipeline in C++ without any graphics API (OpenGL/Vulkan) — just drawing pixels.

## Build

```bash
mkdir build && cd build
cmake ..
make
```

## Run

```bash
./tinyrender
```

Outputs `framebuffer.tga`.

## Structure

| File | Purpose |
|------|---------|
| `main.cpp` | Entry point, scene setup |
| `tgaimage.h/cpp` | TGA image I/O |
| `CMakeLists.txt` | CMake build config |
| `obj/` | Wavefront .obj models |
