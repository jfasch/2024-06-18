# boilerplate/management
cmake_minimum_required(VERSION 3.20)
project(Demo)

if ("${CMAKE_BUILD_TYPE}" STREQUAL Debug OR "${CMAKE_BUILD_TYPE}" STREQUAL "")
  if (${CMAKE_C_COMPILER_ID} STREQUAL GNU)
    string(APPEND CMAKE_C_FLAGS " -O0 -g3 -Wall -Werror")
  endif()
  if (${CMAKE_CXX_COMPILER_ID} STREQUAL GNU)
    string(APPEND CMAKE_CXX_FLAGS " -O0 -g3 -Wall -Werror")
  endif()
endif()

add_subdirectory(bin)
add_subdirectory(libhello)
