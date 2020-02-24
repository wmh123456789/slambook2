cmake_minimum_required( VERSION 2.8 )
project( geometry )

# 添加Eigen头文件
# for MacosX, "/usr/local/include/eigen3"
# for Ubuntu, "/usr/include/eigen3"
include_directories( "/usr/local/include/eigen3" )

add_executable(eigenGeometry eigenGeometry.cpp)
