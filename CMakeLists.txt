cmake_minimum_required (VERSION 2.6)

PROJECT ( HighPerTimer )

SET ( CMAKE_VERBOSE_MAKEFILE on )
set ( CMAKE_CXX_FLAGS "-O0 -g3 -Wall -std=c++17 -lrt -lm -O2")

ADD_SUBDIRECTORY ( lib/libHPTimer)

ADD_SUBDIRECTORY ( app )
