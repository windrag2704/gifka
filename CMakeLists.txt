cmake_minimum_required(VERSION 3.14)
project(gifka)

set(CMAKE_CXX_STANDARD 14)

add_executable(gifka src/main.cpp src/Block.cpp src/Block.h src/GIF.cpp src/GIF.h src/GIFParser.cpp src/GIFParser.h)