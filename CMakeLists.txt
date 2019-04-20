cmake_minimum_required(VERSION 2.8)

project(tbui)

add_library(${PROJECT_NAME} "tbui.c" "tbui.h")

include_directories(${CMAKE_CURRENT_SOURCE_DIR})

add_subdirectory(examples)
