cmake_minimum_required(VERSION 3.28)
project(m22 C)

set(CMAKE_C_STANDARD 90)

add_executable(m22 myset.c
        set.c
        set.h
        parser.h
        parser.c
        exclusive_typedef.h
        sharedParcerStruct.h)
