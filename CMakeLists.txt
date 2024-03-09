cmake_minimum_required(VERSION 3.27)
project(DES)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(DES
        main.cpp
        main.h)
