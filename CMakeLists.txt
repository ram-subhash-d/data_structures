cmake_minimum_required(VERSION 3.14)
project(data_structures)

set(CMAKE_CXX_STANDARD 17)

# --- Main Application ---
add_executable(data_structures_app main.cpp)
target_include_directories(data_structures_app PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/include/)

add_subdirectory(src)