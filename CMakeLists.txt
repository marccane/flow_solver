cmake_minimum_required(VERSION 2.6)
project(flow_solver)
set(CMAKE_C_FLAGS "-g -Wall -std=c99")
add_executable(flow_solver flow_solver.c)
