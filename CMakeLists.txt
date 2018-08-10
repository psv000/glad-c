cmake_minimum_required(VERSION 3.6)

project(glad)

include_directories(include)
add_library( glad src/glad.c include/glad/glad.h include/KHR/khrplatform.h )