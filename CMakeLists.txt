cmake_minimum_required( VERSION 3.0)

project(Lab3)

include_directories( ./src ./test ./include/Lab3)

add_executable( test ./test/Menu.cpp ./src/Lab3.cpp) 