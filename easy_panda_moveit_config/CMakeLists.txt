cmake_minimum_required(VERSION 3.0.2)
project(easy_panda_moveit_config)

find_package(catkin REQUIRED)

catkin_package()


#############
## Install ##
#############

# all install targets should use catkin DESTINATION variables
# See http://ros.org/doc/api/catkin/html/adv_user_guide/variables.html

## Mark other files for installation (e.g. launch and bag files, etc.)
install(FILES
        launch/demo.launch
        launch/moveit.rviz
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
        )
