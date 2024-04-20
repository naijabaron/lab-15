cmake_minimum_required(VERSION 3.16)
project(course C)

set(CMAKE_C_STANDARD 11)

add_executable(course
        libs/data_structures/matrix/matrix.h
        libs/data_structures/matrix/matrix.c
        main.c)

target_link_libraries(libs)