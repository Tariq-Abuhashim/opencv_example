cmake_minimum_required(VERSION 2.8)
project(MatRelated)
find_package(OpenCV REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})
add_executable(MatRelated MatRelated.cpp)
target_link_libraries(MatRelated ${OpenCV_LIBS})
