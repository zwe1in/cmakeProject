cmake_minimum_required(VERSION 3.10 FATAL_ERROR)

project(
    VERSION 0.0.1
    DESCRIPTION "Zewei's Cmake Project demo"
    PROJECT_HOMEPAGE_URL "https://github.com/zwe1in/cmakeProject"
    LANGUAGES C CXX   
)

list(APPEND CMAKE_MODULE_PATH "${CMAKE_SOURCE_DIR}/cmake")

include(BuildInfo)

add_subdirectory(src)
add_subdirectory(external)
add_subdirectory(example)
add_subdirectory(docs)
add_subdirectory(test)
add_subdirectory(packaging)
