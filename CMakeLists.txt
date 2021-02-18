cmake_minimum_required(VERSION 2.8 FATAL_ERROR)

# set the project name
project(Main1)
add_subdirectory(src)


# add the executable
add_executable(Main1 Main1)
target_link_libraries(Main1 OB2)

