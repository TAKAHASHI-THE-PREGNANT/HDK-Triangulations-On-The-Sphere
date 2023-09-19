WIP  
CGAL 2D Triangulations on the Sphere in Houdini  
https://doc.cgal.org/latest/Triangulation_on_sphere_2/index.html#Chapter_2D_Triangulations_on_sphere

## Installation
1. Installing CGAL with Vcpkg
https://doc.cgal.org/latest/Manual/windows.html
```
.\vcpkg.exe install cgal:x64-windows
```
  
2. Build
in Houdini Command Line Tools
```
mkdir build
cd build
cmake -DCMAKE_TOOLCHAIN_FILE=VCPKG_PATH\scripts\buildsystems\vcpkg.cmake ..
cmake --build . --clean-first
```

3. Add PATH

```
__My_Houdini_User_Pref__/bin
```