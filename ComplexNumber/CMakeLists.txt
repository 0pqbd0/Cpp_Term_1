cmake_minimum_required(VERSION 3.28)
project(ComplexNumber)

set(CMAKE_CXX_STANDARD 17)

add_executable(ComplexNumber main.cpp
        complex_number.cpp
        unit_tests.cpp
        complex_header.h
        unit_test_header.h)
