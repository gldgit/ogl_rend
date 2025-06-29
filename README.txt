# ogl_rend

A modern OpenGL renderer built from the ground up, designed for learning and experimentation with real-time graphics programming.

![OpenGL](https://img.shields.io/badge/OpenGL-4.6-blue.svg)
![C++](https://img.shields.io/badge/C++-17-red.svg)
![CMake](https://img.shields.io/badge/CMake-3.16+-green.svg)
![License](https://img.shields.io/badge/license-MIT-brightgreen.svg)

## Quick Start

### Prerequisites

- **CMake** 3.16 or higher
- **C++17** compatible compiler (GCC 7+, Clang 5+, MSVC 2017+)
- **OpenGL 3.3+** compatible graphics driver

### Building

```bash
# Clone the repository
git clone https://github.com/yourusername/ogl_rend.git
cd ogl_rend

# Create build directory
mkdir build && cd build

# Configure and build
cmake ..
cmake --build . --config Release

# Run the renderer
./ogl_rend  # Linux/macOS
# or
ogl_rend.exe  # Windows
```
