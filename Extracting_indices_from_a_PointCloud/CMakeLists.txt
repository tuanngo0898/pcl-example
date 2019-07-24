cmake_minimum_required(VERSION 3.5)
project(pcd_write_test)

# set(CMAKE_VERBOSE_MAKEFILE on)

find_package(PCL REQUIRED)

include_directories(${PCL_INCLUDE_DIRS})
link_directories(${PCL_LIBRARY_DIRS})
add_definitions(${PCL_DEFINITIONS})

add_executable(${PROJECT_NAME} main.cpp)
target_link_libraries(${PROJECT_NAME} ${PCL_LIBRARIES})
