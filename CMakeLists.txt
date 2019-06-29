cmake_minimum_required(VERSION 3.14)
project(gifka)

set(CMAKE_CXX_STANDARD 14)

add_executable(gifka main.cpp Block.cpp Block.h GIF.cpp GIF.h GIFParser.cpp GIFParser.h)