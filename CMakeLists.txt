project(go-icp)

cmake_minimum_required(VERSION 2.8 FATAL_ERROR)

add_executable(go-icp
	jly_main.cpp
	jly_goicp.cpp
	jly_3ddt.cpp
	matrix.cpp
	ConfigMap.cpp
	StringTokenizer.cpp
	)
