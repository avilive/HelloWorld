cmake_minimum_required(VERSION 3.16)

project(main)

add_executable(main ip_filter_main.cpp)

install(TARGETS main)

add_subdirectory(libs)
add_subdirectory(main)
###############
target_link_libraries(${PROJECT_NAME}
    sub::lib1
)
###############
enable_testing()
add_test(NAME main COMMAND main)
