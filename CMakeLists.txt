project( MiniBoost )
cmake_minimum_required( VERSION 2.8 )

include_directories( ${CMAKE_SOURCE_DIR}/include )
add_subdirectory( libs )
add_subdirectory( examples )
