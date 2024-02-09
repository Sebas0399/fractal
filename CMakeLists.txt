cmake_minimum_required(VERSION 3.26)
project(ejercicio01)

set(CMAKE_CXX_STANDARD 17)

add_executable(ejercicio01 main.cpp)
find_package(SFML)
find_package(fmt)

target_link_libraries(ejercicio01 fmt::fmt)
target_link_libraries(ejercicio01 sfml::sfml)
