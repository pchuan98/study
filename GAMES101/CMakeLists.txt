cmake_minimum_required(VERSION 3.5.0)
project(GAMES101 VERSION 0.1.0 LANGUAGES C CXX)

find_package(Eigen3 REQUIRED)
include_directories(EIGEN3_INCLUDE_DIR)

add_executable(GAMES101 day01/main.cpp)