cmake_minimum_required(VERSION 3.27)
project(c_linux_containers C)

set(CMAKE_C_STANDARD 23)

add_executable(c_linux_containers main.c
        includes/container.h
        src/container.c)
