cmake_minimum_required(VERSION 3.17)
project(ex1)

set(CMAKE_CXX_STANDARD 14)

add_executable(ex1 main.cpp anomaly_detection_util.h anomaly_detection_util.cpp)