cmake_minimum_required(VERSION 3.13)

project(vk-renderer)

set_property(GLOBAL PROPERTY USE_FOLDERS ON)
set_property(DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR} PROPERTY VS_STARTUP_PROJECT vk-renderer)

add_subdirectory(src)