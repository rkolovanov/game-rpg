cmake_minimum_required(VERSION 3.16)
project(game-engine-map)

set(SOURCES Map.cpp)
add_library(game-engine-map SHARED ${SOURCES})
