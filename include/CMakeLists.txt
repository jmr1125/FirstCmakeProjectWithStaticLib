cmake_minimum_required(VERSION 3.0)
project(exeandlib VERSION 1.0)

set(LIBRARY_OUTPUT_PATH "${PROJECT_BINARY_DIR}/lib")

add_library(lib STATIC main.cpp)
