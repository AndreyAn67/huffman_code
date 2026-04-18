cmake_minimum_required(VERSION 3.10)
project(HuffmanCode
    VERSION 1.0.0
    LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)

add_executable(HuffmanCode main.cpp huffman.cpp)