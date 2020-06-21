cmake_minimum_required(VERSION 3.16.3)
project (app-kitchen)

include_directories(../include)

file(GLOB SOURCES "*.cpp")

add_executable(app-kitchen ${SOURCES})
