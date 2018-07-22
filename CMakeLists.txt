cmake_minimum_required(VERSION 3.0)

set(CMAKE_MODULE_PATH "${CMAKE_CURRENT_LIST_DIR}/Modules")

project(pchtest CXX CXXPCH)

add_subdirectory(Tests)
