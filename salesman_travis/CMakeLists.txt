cmake_minimum_required(VERSION 3.9)
project(salesman)

set(CMAKE_CXX_STANDARD 14)

add_executable(salesman main.cpp graph.h graph.cpp MST.cpp TSP.h TSP.cpp check.cpp test.cpp)
