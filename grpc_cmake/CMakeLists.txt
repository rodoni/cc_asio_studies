cmake_minimum_required(VERSION 3.15)

project(grpc_error_handling LANGUAGES CXX)

set(CMAKE_MODULE_PATH "${CMAKE_SOURCE_DIR}/cmake")

add_subdirectory(client)
#add_subdirectory(server)
add_subdirectory(proto)
