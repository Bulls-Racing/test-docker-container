cmake_minimum_required(VERSION 3.22)
set(project "VDS")
set(output_name "vds")
project(${project})

set(CMAKE_CXX_STANDARD 23)

add_executable(${project} vds.cpp vds.h)
set_target_properties(${project} PROPERTIES OUTPUT_NAME ${output_name})
