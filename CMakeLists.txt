cmake_minimum_required(VERSION 3.16)
project(hello_world LANGUAGES CXX)

# Choose your standard once, everywhere
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(hello_world helloworld.cpp)