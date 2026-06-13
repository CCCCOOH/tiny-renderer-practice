# tiny-renderer-practice

一个从零实现的软件渲染器，跟随经典教程 [tinyrenderer](https://github.com/ssloy/tinyrenderer) 学习图形学管线。纯 C++ 实现，不依赖任何图形 API（OpenGL/Vulkan），核心就是画像素。

## 构建

```bash
mkdir build && cd build
cmake ..
make
```

## 运行

```bash
./tinyrender
```

输出 `framebuffer.tga`。

## 文件结构

| 文件 | 用途 |
|------|------|
| `main.cpp` | 入口、场景设置 |
| `tgaimage.h/cpp` | TGA 图片读写 |
| `CMakeLists.txt` | CMake 构建配置 |
| `obj/` | Wavefront .obj 模型 |
