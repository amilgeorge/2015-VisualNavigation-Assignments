add_executable(t4_waypoint_publisher waypoint_publisher.cpp)
target_link_libraries(t4_waypoint_publisher ${catkin_LIBRARIES})
add_dependencies(t4_waypoint_publisher ${catkin_EXPORTED_TARGETS})