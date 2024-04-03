cmake_minimum_required(VERSION 3.27)

add_compile_options(-Wall -Wextra -Wpedantic -Werror)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

project(HelloWorld)
add_executable(HelloWorld HelloWorld.cpp)