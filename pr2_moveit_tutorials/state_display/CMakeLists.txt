add_executable(state_display_tutorial src/state_display_tutorial.cpp)
target_link_libraries(state_display_tutorial ${catkin_LIBRARIES} ${Boost_LIBRARIES})
install(TARGETS state_display_tutorial DESTINATION ${CATKIN_PACKAGE_LIB_DESTINATION})
