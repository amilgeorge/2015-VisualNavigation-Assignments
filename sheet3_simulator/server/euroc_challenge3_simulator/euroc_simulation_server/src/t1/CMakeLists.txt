add_executable(t1_dataset_provider dataset_provider.cpp)
add_dependencies(t1_dataset_provider ${catkin_EXPORTED_TARGETS})
target_link_libraries(t1_dataset_provider ${catkin_LIBRARIES})