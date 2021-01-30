cmake_minimum_required(VERSION 3.17.4)

project(HelloCMake)

# Ensure -std=c++xx instead of -std=g++xx
set(CMAKE_CXX_EXTENSIONS OFF)

# Support folders in IDEs
set_property(GLOBAL PROPERTY USE_FOLDERS ON)

add_subdirectory(source)
add_subdirectory(application)
