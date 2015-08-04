cmake_minimum_required(VERSION 2.8)
project(hello-world C)

set(HELLOWORLD_SOURCES src/program.c)
add_executable(hello-world ${HELLOWORLD_SOURCES})
