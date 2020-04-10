cmake_minimum_required(VERSION 3.15)
project(opencv-uc3m)
set(CMAKE_CXX_STANDARD 14)
include_directories(${OpenCV_INCLUDE_DIRS})
link_directories(${OpenCV_LINK_DIRS})


find_package(OpenCV 4.2 REQUIRED)



add_executable(Ejemplo1 Ejemplo1.cpp)
