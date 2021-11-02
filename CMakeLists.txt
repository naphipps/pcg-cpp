cmake_minimum_required(VERSION 3.21.4)
project(pcg-cpp VERSION 1.0.0.0 LANGUAGES CXX)

add_library(${PROJECT_NAME} INTERFACE)

target_include_directories(${PROJECT_NAME} INTERFACE "${PROJECT_SOURCE_DIR}/include")
target_compile_features(${PROJECT_NAME} INTERFACE cxx_std_11)