cmake_minimum_required(VERSION 3.15)

add_library(weapon DragonSword.cpp Knife.cpp)

target_include_directories(weapon INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})