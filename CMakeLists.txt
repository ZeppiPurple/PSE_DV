cmake_minimum_required(VERSION 3.21)
project(PSE_DV)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(PSE_DV
        main.cpp
        main.h)
