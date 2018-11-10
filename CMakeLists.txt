cmake_minimum_required(VERSION 3.10)
project(playground)

add_executable(Hello ${CMAKE_SOURCE_DIR}/src/main.c)

install(TARGETS Hello DESTINATION bin)