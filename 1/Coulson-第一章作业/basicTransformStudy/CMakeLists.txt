cmake_minimum_required( VERSION 2.8 )
project( basicTransformStudy )

include_directories( "/usr/include/eigen3" )

# add options
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_BUILD_TYPE Debug)
add_executable(basicTransformStudy src/basic_transform_study.cpp )
