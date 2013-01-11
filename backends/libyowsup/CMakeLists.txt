cmake_minimum_required(VERSION 2.6)

#FILE(GLOB SRC *.c *.cpp)
#
#ADD_EXECUTABLE(spectrum2_libyowsup ${SRC})
#
#if (CMAKE_COMPILER_IS_GNUCXX)
#if (NOT WIN32)
#target_link_libraries(spectrum2_libyowsup transport pthread ${Boost_LIBRARIES} ${SWIFTEN_LIBRARY} ${LOG4CXX_LIBRARIES})
#else()
#target_link_libraries(spectrum2_libyowsup transport ${Boost_LIBRARIES} ${SWIFTEN_LIBRARY} ${LOG4CXX_LIBRARIES})
#endif()
#else()
#target_link_libraries(spectrum2_libyowsup transport ${PROTOBUF_LIBRARY} ${Boost_LIBRARIES} ${SWIFTEN_LIBRARY} ${LOG4CXX_LIBRARIES})
#endif()

#INSTALL(TARGETS spectrum2_libyowsup RUNTIME DESTINATION bin)
INSTALL(PROGRAMS spectrum2_libyowsup_backend DESTINATION bin )

