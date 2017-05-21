cmake_minimum_required (VERSION 2.6)
project (travis_cmake_gcc_cpp98)
add_executable(travis_cmake_gcc_cpp98 main.cpp)

set_property(TARGET travis_cmake_gcc_cpp98 PROPERTY CXX_STANDARD 98)
set_property(TARGET travis_cmake_gcc_cpp98 PROPERTY CXX_STANDARD_REQUIRED ON)