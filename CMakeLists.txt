cmake_minimum_required(VERSION 3.10)
project(wuji_hand_description)

find_package(catkin REQUIRED)

catkin_package()

install(
    DIRECTORY launch meshes rviz urdf
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
