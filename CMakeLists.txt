cmake_minimum_required(VERSION 3.6)   # CMake version check
project(clingalg)             

include_directories( ${CMAKE_SOURCE_DIR} )
#Headers
file(GLOB HEADERS *.h)

#Source 
set(SOURCE_FILES test_all.c)

add_executable(clingalg ${SOURCE_FILES} ${HEADERS})
