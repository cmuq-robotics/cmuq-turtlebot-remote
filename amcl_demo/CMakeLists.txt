cmake_minimum_required(VERSION 2.8.3)
project(amcl_demo)

find_package(catkin REQUIRED COMPONENTS)

catkin_package()

install(DIRECTORY launch
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

install(DIRECTORY param
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

install(DIRECTORY icons
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

install(DIRECTORY interactions
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
