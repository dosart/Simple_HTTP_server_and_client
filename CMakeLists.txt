cmake_minimum_required(VERSION 3.0)

project(Simple_HTTP_server_and_client VERSION 0.1.0 LANGUAGES C)

set(CMAKE_C_STANDARD 11)

add_executable(server src/http_server.c)
add_executable(client src/http_client.c)
