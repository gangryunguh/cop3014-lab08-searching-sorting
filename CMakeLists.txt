cmake_minimum_required(VERSION 3.14)
project(cop3014_lab08_searching_sorting)

set(CMAKE_CXX_STANDARD 11)

add_executable(linear_search.exe linear_search.cpp)
add_executable(bubble_sort.exe bubble_sort.cpp)
add_executable(selection_sort.exe selection_sort.cpp)
add_executable(binary_search.exe binary_search.cpp)
