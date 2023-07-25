cmake_minimum_required(VERSION 3.15)

add_subdirectory(Hero)
add_subdirectory(Monster)
add_subdirectory(weapon)

add_executable(game game.cpp)

target_link_libraries(game PUBLIC
    Hero Monster weapon)