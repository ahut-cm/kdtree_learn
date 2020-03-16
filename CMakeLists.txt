cmake_minimum_required(VERSION 3.5.1)
project(bstree)

set(CMAKE_CXX_STANDARD 14)
SET(CMAKE_C_COMPILER g++)
add_compile_options(-std=c++11)


add_executable(bstree testKDTree.cpp)