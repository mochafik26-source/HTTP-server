cmake_minimum_required(VERSION 3.16)

project(HttpServer)

set(CMAKE_CXX_STANDARD 17)

add_executable(server
    src/main.cpp
    src/server.cpp
    src/router.cpp
)
