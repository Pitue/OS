cmake_minimum_required(VERSION 3.20)
project(OS C)

set(CMAKE_C_STANDARD 99)

add_executable(OS
        "inc/include.h"

        "./src/main.c")