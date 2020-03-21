cmake_minimum_required(VERSION 3.10)

project(cmake_test_exe)

include_directories(${PROJECT_SOURCE_DIR})
add_executable(app main.cpp)
