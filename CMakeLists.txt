cmake_minimum_required(VERSION 3.22.0)
project(CMake_Lesson10_02)

set (SOURCES 
03.cpp Figure.cpp Triangle.cpp RightTriangle.cpp EquilateralTriangle.cpp 
IsoscelesTriangle.cpp Quadrilateral.cpp Parallelogram.cpp Rectangle.cpp 
Rhomb.cpp Square.cpp PrintFigure.cpp)

set (HEADERS 
Figure.h Triangle.h RightTriangle.h EquilateralTriangle.h 
IsoscelesTriangle.h Quadrilateral.h Parallelogram.h 
Rectangle.h Rhomb.h Square.h PrintFigure.h)

add_executable(${PROJECT_NAME} ${SOURCES} ${HEADERS})
