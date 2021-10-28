# cmake_minimum_required(VERSION <specify CMake version here>)
project(Assignment_5)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Assignment_5
        TicTacToe.cpp
        TicTacToe.h)
