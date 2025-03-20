cmake_minimum_required(VERSION 3.14)
project(StrongTests)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

file(GLOB SOURCES "*.cpp")
add_executable(strong_tests ${SOURCES})
