cmake_minimum_required(VERSION 3.6)
project(k_means_parallel)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -fopenmp")
set(CMAKE_CXX_STANDARD 14)

add_executable(k_means_parallel
        Cluster.cpp
        main.cpp
        Point.cpp)
