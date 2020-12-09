cmake_minimum_required(VERSION 3.16)
project(C_App C)

set(CMAKE_C_STANDARD 99)

add_executable(C_App us-extern/main.c us-extern/support.c)