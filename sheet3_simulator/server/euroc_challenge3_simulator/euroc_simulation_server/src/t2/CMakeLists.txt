add_executable(t2_dataset_provider dataset_provider.cpp)
add_dependencies(t2_dataset_provider ${catkin_EXPORTED_TARGETS})
target_link_libraries(t2_dataset_provider ${catkin_LIBRARIES})