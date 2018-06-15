cmake_minimum_required(VERSION 3.9)
project(lept C)

set(CMAKE_C_STANDARD 99)

add_library(lept lept.c)
add_executable(lept_test test.c)
target_link_libraries(lept_test lept)