cmake_minimum_required(VERSION 3.28.0)
project(sodium VERSION 0.0.0 LANGUAGES C)

add_executable(na)
target_include_directories(na PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/include)

add_subdirectory(src)