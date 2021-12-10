cmake_minimum_required(VERSION 3.16)

project(ip_filter)

add_executable(ip_filter ip_filter_main.cpp)

#install(TARGETS ip_filter)

#add_subdirectory(libs)
#add_subdirectory(main)


###############
#target_link_libraries(${PROJECT_NAME}
#    sub::lib1
#)
###############
#enable_testing()
#add_test(NAME ip_filter COMMAND ip_filter)
