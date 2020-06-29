cmake_minimum_required(VERSION 2.8)

set (PROJECT FORTtest)

project(${PROJECT})

set(HEADERS foo.h)

set(SOURCES foo.cpp main.cpp)

add_executable(${PROJECT} ${HEADERS} ${SOURCES})

