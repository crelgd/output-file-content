cmake_minimum_required(VERSION 3.5)
project(main)

set(SOURCES
    src/main.cpp
    src/FileSystem/FileSystem.cpp
)

set(LIBS
    include/FileSystem
    include
)

include_directories(${LIBS})
add_executable(main ${SOURCES})
