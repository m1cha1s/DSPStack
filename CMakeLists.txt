cmake_minimum_required(VERSION 3.16)

add_subdirectory(DSPStack)

project(DSPStackEXE)

add_executable(DSPStackEXE main.cpp)

target_link_libraries(DSPStackEXE PRIVATE DSPStack)