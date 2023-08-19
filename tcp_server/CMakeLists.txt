project(tcp_server)
cmake_minimum_required(VERSION 3.16)

add_executable(tcp_server main.cpp)
target_link_libraries(tcp_server PRIVATE ${USED_LIBS})