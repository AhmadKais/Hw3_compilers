cmake_minimum_required(VERSION 3.24)
project(CompilerExersice)

set(CMAKE_CXX_STANDARD 17)

add_executable(CompilerExersice ast.h
        lex.yy.c
        main.cpp
        main.h
        miny.tab.cpp
        miny.tab.hpp
        )
