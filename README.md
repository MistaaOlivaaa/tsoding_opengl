# OpenGL Project with GLFW

A minimal OpenGL project using GLFW for window/input handling, with vertex/fragment shaders.




## ⚙️ Dependencies
- **GLFW** (for window/input management)
- **OpenGL** (core graphics library)
- **GCC/Clang** (Linux/macOS) or **MSVC** (Windows)


## 🛠️ Build & Run

```bash
git clone https://github.com/MistaaOlivaaa/tsoding_opengl.git
cd tsoding_opengl
```

### Linux/macOS (Makefile)
```bash
make        # Compile
./a.out     # Run
```

### Windows (MSVC)
 ```bash
build_msvc.bat
main.exe
```
### Manual Compilation (GCC)
```bash
gcc main.c glextloader.c -o opengl_app -lglfw -lGL -lm
./opengl_app
```
