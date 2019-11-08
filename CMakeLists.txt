cmake_minimum_required(VERSION 3.14)
project(trim_m3u C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(trim_m3u
        trim-m3u.c
        trim-m3u.h)
