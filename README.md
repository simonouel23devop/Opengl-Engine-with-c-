<img width="1262" height="702" alt="Screenshot 2026-09-15 210806" src="https://github.com/user-attachments/assets/f7317ecf-97a0-478f-a325-ffcb135d4edb" />



# GD-Engine

GD-Engine is an educational game engine built step by step throughout a structured series of lessons. The goal of this repository is to provide a clear, progressive learning path for those who want to deeply understand how game engines are built from scratch using modern C++ and core rendering/physics/input concepts.

---

## 📚 Lessons Structure

All detailed lesson sources are stored in the **`lessons/`**  directory.
Each lesson introduces a new subsystem or feature.
You can also browse through the **Git tags**, where every tag represents a specific lesson checkpoint — allowing you to view the engine exactly as it was at that step in development.
Additionally, each commit contains the full engine state up to that point, including all lessons from the very beginning up to the commit you are currently inspecting.

---

## 🎯 Purpose of the Engine

This engine is not meant to compete with production engines like Unity or Unreal.  
Instead, it serves as a **learning-focused codebase**, designed to reveal how:

- Rendering pipelines are built from zero.
- Physics and collision systems function internally.
- Scene graphs, components, UI systems and scripting expand engine architecture.
- Audio integrated
- Real 2D and 3D gameplay logic is implemented.

Every subsystem is introduced gradually with detailed breakdowns and simple C++ implementations.

---

## 💻 Supported Platforms

The engine is designed to be **cross-platform** and currently targets:

- ✅ **Windows**
- ✅ **macOS**
- ✅ **Linux**

---

## 🛠️ Technologies & Standards

| Technology        | Details                               |
|------------------|---------------------------------------|
| **Language**      | C++ (C++17 standard)                  |
| **Build System**  | CMake                                 |
| **Graphics**      | OpenGL                                |
| **Window Management**      | GLFW                                |

---

## 📂 Project Structure

| Folder             | Description |
|------------------|------------|
| `source/`         | Project source code |
| `CMakeLists.txt`  | Project build configuration |
| `engine/source/`  | Engine source code |
| `engine/thirdparty/` | Engine third-party libraries |
| `engine/CMakeLists.txt`  | Engine build configuration |
| `lessons/`        | Lesson materials |

---

## ⚙️ Build Instructions

You can build the engine using one of two approaches:

### 1. Generate Project via Script
- `./gen_proj_vs2022.bat` for Visual Studio 2022
- `./gen_proj_xcode.sh` for Xcode
Then open the generated project from `build` folder in your preferred IDE.

### 2. Open Repository with IDE in CMake Mode (Recommended)
Simply open the repository root in **CLion / Visual Studio Code / Visual Studio (CMake mode)** and let it configure automatically.

---

## 🌱 Educational Focus

This repository evolves lesson by lesson.  
You are encouraged to explore the tags chronologically and compare how the engine grows through each commit.  
It’s a **transparent and developer-friendly journey** into engine architecture and low-level game development.
