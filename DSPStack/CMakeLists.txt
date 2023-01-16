project(DSPStack)

FILE(GLOB DSPStackSrc *.cpp)

add_library(DSPStack ${DSPStackSrc})

target_include_directories(DSPStack PUBLIC .)