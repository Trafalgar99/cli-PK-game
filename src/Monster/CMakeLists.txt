cmake_minimum_required(VERSION 3.15)

add_library(Monster Monster.cpp)

target_include_directories(Monster INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})

target_link_libraries(Monster Hero weapon)