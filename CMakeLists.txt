cmake_minimum_required(VERSION 3.24)
project(InviteGroup)

set(CMAKE_CXX_STANDARD 14)
find_package(OpenCV)
include_directories(${OpenCV_INCLUDE_DIRS})
add_executable(InviteGroup main.cpp)
target_link_libraries(InviteGroup ${OpenCV_LIBS})