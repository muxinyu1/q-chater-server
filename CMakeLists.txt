cmake_minimum_required(VERSION 3.22)

project(Qtalk)

set(CMAKE_CXX_STANDARD 20)

add_executable(Qtalk main.cpp lib.cpp)

target_link_libraries(Qtalk sqlite3)