cmake_minimum_required(VERSION 4.0)
project(Raytracer VERSION 0.1.0 LANGUAGES C CXX)

add_executable(Raytracer main.cpp)

target_include_directories(Raytracer PRIVATE includes)