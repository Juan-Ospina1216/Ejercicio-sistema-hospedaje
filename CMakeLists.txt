cmake_minimum_required(VERSION 3.24)
project(Ejercicio_sistema_hospedaje)

include_directories(lib)
include_directories(src)
include_directories(test)

add_subdirectory(lib/googleTest)
add_subdirectory(src)
add_subdirectory(test)

set(CMAKE_CXX_STANDARD 17)

add_executable(Ejercicio_sistema_hospedaje main.cpp)
