cmake_minimum_required(VERSION 3.4)
project(form)
add_library(create_form STATIC formatter.cpp)
include_directories(formatter_lib)
