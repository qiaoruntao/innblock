cmake_minimum_required(VERSION 3.19)
project(innblock)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(innblock
        an_block.cpp
        an_block.h
        an_page.h
        main.cpp
        myfine.h
        mysqldefine.h
        tool.cpp
        tool.h
        usage_check.cpp
        usage_check.h)
