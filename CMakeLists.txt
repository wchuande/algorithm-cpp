cmake_minimum_required(VERSION 3.19)
project(algorithm-cpp)

set(CMAKE_CXX_STANDARD 11)

add_executable(study main.cpp)
add_executable(search search.cc)
add_executable(skiplist skiplist.cc)
add_executable(skiplistwithtwopointer skiplistwithtwopointer.cc)
