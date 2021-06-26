# The minimum version
cmake_minimum_required(VERSION 2.8)

# set C++ 11 declaration
set(CMAKE_CXX_STANDARD 11)

# project name
project(cpp-cmake-circle-ci)

# set build output path
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_SOURCE_DIR}/bin)

# set .h file path
include_directories(${PROJECT_SOURCE_DIR}/include)

# set build output file
add_executable(point_test ${PROJECT_SOURCE_DIR}/src/pointTest.cpp)
