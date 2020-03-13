cmake_minimum_required(VERSION 3.5)
project(trevisTest)


SET(SOURCE
	src/main.cpp
)


add_executable(testt ${SOURCE})
TARGET_LINK_LIBRARIES(testt)


