cmake_minimum_required(VERSION 3.10)
project(Sudoku-Generator)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)

add_executable(sudoku
    main.cpp
    src/board.cpp
    src/solver.cpp
    src/generator.cpp
)
