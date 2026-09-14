cmake_minimum_required(VERSION 3.16)

if(WIN32)
	set(CMAKE_OBJECT_PATH_MAX 200)
endif()

include($ENV{IDF_PATH}/tools/cmake/project.cmake)

project(lab7_2_softap_provisioning)
