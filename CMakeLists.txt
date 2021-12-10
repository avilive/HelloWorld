cmake_minimum_required(VERSION 3.16)

project(main)

set(SOURCES
    main.cpp 
)

add_executable(${PROJECT_NAME} main.cpp)

add_subdirectory(libs)
add_subdirectory (main)

enable_testing()
add_test(NAME main COMMAND main)
