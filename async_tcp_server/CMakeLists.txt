project(async_tcp_server)
cmake_minimum_required(VERSION 3.16)

add_executable(async_tcp_server main.cpp)
target_link_libraries(async_tcp_server PRIVATE ${USED_LIBS})