cmake_minimum_required(VERSION 3.22)
project(ECE4400_Project)

set(CMAKE_CXX_STANDARD 14)

add_library(jsoncpp STATIC jsoncpp/dist/jsoncpp.cpp)

add_executable(ECE4400_Project
        main.cpp
        linkedList.cpp
        linkedList.h
        dll.cpp
        Stack.cpp
        Stack.h
        queue.cpp
        queue.h
        jsoncpp/dist/jsoncpp.cpp
        )
