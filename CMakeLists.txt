cmake_minimum_required(VERSION 3.16)

project(main)


add_subdirectory(libs)
add_subdirectory (main)

enable_testing()
add_test(NAME main COMMAND main)
