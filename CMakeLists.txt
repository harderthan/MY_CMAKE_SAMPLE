cmake_minimum_required(VERSION 2.8.12 )

project(CMAKE_Sample_Project)

set(SOURCES
    main.cpp
)

#set(Directory_PATH
#    
#)

set (CMAKE_CXX_FLAGS "--std=gnu++11 ${CMAKE_CXX_FLAGS}")

#include_directories(${Directory_PATH}) 

add_executable(${PROJECT_NAME} ${SOURCES})  

