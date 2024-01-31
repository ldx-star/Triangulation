cmake_minimum_required(VERSION 3.5)
project(Triangulation)
set(CMAKE_CXX_STANDARD 11)

find_package(Eigen3 REQUIRED)
include_directories(${EIGEN3_INCLUDE_DIRS})

add_executable(Test_Triangulation test_triangle.cpp)

