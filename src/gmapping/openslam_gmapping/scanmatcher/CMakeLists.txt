add_library(scanmatcher eig3.cpp scanmatcher.cpp scanmatcherprocessor.cpp )
target_link_libraries(scanmatcher sensor_range utils)

install(TARGETS scanmatcher DESTINATION ${CATKIN_PACKAGE_LIB_DESTINATION})
