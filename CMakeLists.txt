cmake_minimum_required(VERSION 3.20)
project(sudoku)

set(CMAKE_CXX_STANDARD 20)

add_executable(lifegame src/main.cpp
        src/lifegame.cpp        src/include/lifegame.h)
target_include_directories(lifegame PUBLIC src/include)
