cmake_minimum_required(VERSION 3.20)
project(Gl LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED On)
set(CMAKE_CXX_EXTENSIONS Off)

set(CMAKE_CXX_COMPILER g++)

#set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
#set(EXECUTABLE_OUTPUT_PATH ${CMAKE_SOURCE_DIR})

add_subdirectory(src/main_files)
add_subdirectory(src/Shaders)
add_subdirectory(src/Textures)


