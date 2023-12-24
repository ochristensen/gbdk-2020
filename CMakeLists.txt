cmake_minimum_required(VERSION 3.28)

project(gbdk C CXX ASM)
set(CMAKE_C_STANDARD 17)
set(CMAKE_CXX_STANDARD 17)

add_subdirectory(gbdk-support)
add_subdirectory(gbdk-lib)
