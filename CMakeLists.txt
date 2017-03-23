cmake_minimum_required(VERSION 3.5)
project(artoolkit_reading)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    .gitignore
    LICENSE
    README.md)

add_executable(artoolkit_reading ${SOURCE_FILES})