cmake_minimum_required(VERSION 3.4)
project(code_compile)
set(CMAKE_CXX_FLAGS ${CMAKE_CXX_FLAGS} "-std=c++11")
add_executable(${PROJECT_NAME}_test main.cpp)
