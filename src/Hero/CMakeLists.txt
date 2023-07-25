cmake_minimum_required(VERSION 3.15)

add_library(Hero Hero.cpp)

target_include_directories(Hero INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})

target_link_libraries(Hero Monster weapon)