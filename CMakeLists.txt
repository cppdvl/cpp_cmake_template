cmake_minimum_required(VERSION 3.10)
project(prj CXX)


add_executable(${PROJECT_NAME} main.cpp)
set_property(TARGET ${PROJECT_NAME} PROPERTY CXX_STANDARD 20)


#[[
target_include_directories(${PROJECT_NAME} PRIVATE folders....) 

Avoid target_include_directories and prefer find_library() 

Avoid target_include_directories and prefer find_library() 



]] 
