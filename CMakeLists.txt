cmake_minimum_required(VERSION 3.0)

set(ROBOT_NAME inail2upperbody)
project(iit-${ROBOT_NAME}-ros-pkg VERSION 1.0.0)

include(GenerateXrdf.cmake)

## add sub-packages
add_subdirectory(inail2upperbody_urdf)

