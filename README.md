# FinalCode_QT_OptiX

# HOW TO INSTALL

## Dependences
*  Visual Studio 2017 for Windows
*  CUDA 10.1
*  OptiX 7 SDK
*  CakeMAke

## Build

- **Install** the packages listed above.
- **Clone** the respository (or download).
- Open **CMake**.
  -point "**source directory**" to the downloaded source directory
  - point "**build directory**" to */build* (the directory should be created inside the source directory folder)
  - click '**configure**', then specify the generator as Visual Studio 2017 and the Optional platform as x64. If appears some red warning click configure again, it could solve the       problem.
  
  - click '**generate**' (this creates a Visual Studio project and solutions)
  
- To enter the project enter the build folder, where you can open the Visual Studio solutions. 

```
NOTE: To run one project you must set it as startup project inside visual Studio.
NOTE2: It is possible that you could need to move the support folder from the OptiX SDK folder to this folder.
```

NOTE: Need to add de coomom folder and the Conference.obj