cmake_minimum_required(VERSION 3.25)
project(iterator)

set(CMAKE_CXX_STANDARD 23)

add_executable(iterator main.cpp include/Iterator.hpp include/Container.hpp include/Data.hpp)
