cmake_minimum_required(VERSION 3.5)
project(CLionProjects)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES
        #main.c
        quicksort.c
        )
add_executable(CLionProjects ${SOURCE_FILES})