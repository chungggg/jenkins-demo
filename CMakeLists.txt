cmake_minimum_required(VERSION 3.16)
project(jenkins_demo)

set(CMAKE_CXX_STANDARD 14)

add_library(jenkins_demo SHARED library.cpp library.h)