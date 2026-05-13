cmake_minimum_required(VERSION 3.14)
project(data_structures)

set(CMAKE_CXX_STANDARD 17)

# --- Main Application ---
add_executable(data_structures_app main.cpp)

add_subdirectory(src)