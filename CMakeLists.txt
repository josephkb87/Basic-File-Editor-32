cmake_minimum_required(VERSION 3.24)
project(Basic_File_Editor_32)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Basic_File_Editor_32
        Basic_File_Editor_WIN_32_private.h
        main.cpp)
