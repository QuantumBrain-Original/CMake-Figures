cmake_minimum_required (VERSION 3.20)

project ("CMake-Figures")

add_executable (CMake-Figures "CMake-Figures.cpp" Modules/sFigures.cpp Modules/Triangles/sTriangles.cpp Modules/Triangles/sRectangularTriangles.cpp Modules/Triangles/sIsoscelesTriangles.cpp Modules/Triangles/sEquilateralTriangles.cpp Modules/Quadrangles/sQuadrangles.cpp Modules/Quadrangles/sParallelograms.cpp Modules/Quadrangles/sRectangles.cpp Modules/Quadrangles/sRhombus.cpp Modules/Quadrangles/sSquares.cpp)
