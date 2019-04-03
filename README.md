# nc-rd-facemask
Facemask C++

# Prepare OpenCV source
- macOS: Install form homebrew
- Windows: download windows pack, extract and put opencv folder to `D:/_Program Files/`

# Build
```
mkdir build
cd build
cmake -DCMAKE_GENERATOR_PLATFORM=x64 -DCMAKE_CL_64=1 -Ax64 ..
cmake --build . --config Release
```

# For CLion
- Build configuration -> Edit -> Select CMake Application target -> Working directory point to current project path.
- Note for windows:
Remember setting arch support is x86_amc64 (File -> Settings -> Build, Execution, Deployment -> Toolchains -> Visual Studio, Architecture: x86_amd64)
