cmake_minimum_required(VERSION 3.5)
project(HelloWord_ED)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(HelloWord_ED ${SOURCE_FILES})