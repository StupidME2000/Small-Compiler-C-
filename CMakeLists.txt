cmake_minimum_required(VERSION 3.28)
project(Small_Compiler_C__)

set(CMAKE_CXX_STANDARD 14)

include_directories("CSE 340 - Project 3")

add_executable(Small_Compiler_C__
        "CSE 340 - Project 3/compiler.cc"
        "CSE 340 - Project 3/compiler.h"
        "CSE 340 - Project 3/inputbuf.cc"
        "CSE 340 - Project 3/inputbuf.h"
        "CSE 340 - Project 3/ir_debug.cc"
        "CSE 340 - Project 3/ir_debug.h"
        "CSE 340 - Project 3/lexer.cc"
        "CSE 340 - Project 3/lexer.h"
#        "CSE 340 - Project 3/main.c"
        "CSE 340 - Project 3/main.cc")
