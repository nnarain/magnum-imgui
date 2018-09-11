cmake_minimum_required(VERSION 3.0.2)

set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} "${PROJECT_SOURCE_DIR}/modules/")

option(BUILD_EXAMPLE "Build example" ON)
option(FIND_IMGUI "Find imgui library" ON)
option(BUILD_SHARED_LIBS "Build shared library" OFF)
set(CMAKE_WINDOWS_EXPORT_ALL_SYMBOLS ON)

add_subdirectory(src)

