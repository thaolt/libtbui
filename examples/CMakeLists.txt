cmake_minimum_required(VERSION 2.8)

project(examples)

add_executable(simple "simple.c")

target_link_libraries(simple tbui)
