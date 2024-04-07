cmake_minimum_required(VERSION 3.23)
project(TT12324_codigo C)

set(CMAKE_C_STANDARD 11)

include_directories(Sourcecode)

add_executable(TT12324_codigo
        Sourcecode/random_data.c
        Sourcecode/random_data.h
        Sourcecode/random_data_prb.c)
