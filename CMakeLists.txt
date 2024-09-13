
cmake_minimum_required(VERSION 3.10)
project(my_project)

set(SRC_FILES src/main.cpp)
set(INCLUDE_DIRS include)

add_executable(my_project ${SRC_FILES})
target_include_directories(my_project PRIVATE ${INCLUDE_DIRS})
