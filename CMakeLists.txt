cmake_minimum_required(VERSION 3.26)
project(Calculator)

set(CMAKE_CXX_STANDARD 23)

add_executable(Calculator main.cpp
        main.h
        Calculator_Source.cpp)
