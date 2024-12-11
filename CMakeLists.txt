cmake_minimum_required(VERSION 3.14)

project(cpp-autoscan VERSION 1.0 LANGUAGES CXX)

set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
add_executable(cpp-autoscan main.cpp)
target_compile_features(cpp-autoscan PRIVATE cxx_std_20)