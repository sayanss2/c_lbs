cmake_minimum_required(VERSION 3.13)
project(c_lbs C)

set(CMAKE_C_STANDARD 11)

include_directories(.)
include_directories(main)

add_executable(c_lbs
        main/main.c)
