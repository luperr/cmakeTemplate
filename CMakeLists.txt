cmake_minimum_required(VERSION 3.5)

set(CMAKE_CXX_FLAG "${CMAKE_CXX_FLAGS} -std=c++14")

add_compile_options(-Wall -Wextra -Wpedantic)

add_executable(main main.cpp)
