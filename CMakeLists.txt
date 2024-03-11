cmake_minimum_required(VERSION 3.22)
project(kspwlo_cmake)

set(CMAKE_CXX_STANDARD 23)

add_executable(kspwlo_cmake main.cpp
        algorithms/completeness.cpp
        algorithms/esx.cpp
        algorithms/kspwlo.hpp
        algorithms/multipass.cpp
        algorithms/onepass.cpp
        algorithms/onepass_plus.cpp
        algorithms/skyline.cpp
        algorithms/svp_plus.cpp
        model/graph.hpp
        model/graph.cpp
        tools/astar.cpp
        tools/dijkstra.cpp
        tools/tools.hpp)
