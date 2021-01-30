cmake_minimum_required(VERSION 3.13)
project(HelloCMake)

add_library(myLib "")

add_subdirectory(include)
add_subdirectory(source)
