cmake_minimum_required(VERSION 3.14)

project(
  sk_cpp_server
  LANGUAGES CXX
  VERSION 0.1.0
)

set(CMAKE_CXX_STANDARD 17)

# https://stackoverflow.com/questions/9345792/cmake-executable-location
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR})

add_subdirectory(./src)
