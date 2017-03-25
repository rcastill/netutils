cmake_minimum_required(VERSION 2.8.9)

set(PROJECT_NAME netutils)
project(${PROJECT_NAME})

set(LIB_SRC src/netutils.c)
include_directories(src)

add_library(${PROJECT_NAME} STATIC ${LIB_SRC})
