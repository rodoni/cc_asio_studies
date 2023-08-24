project(udp_server)
cmake_minimum_required(VERSION 3.16)

add_executable(udp_server main.cpp)
target_link_libraries(udp_server PRIVATE ${USED_LIBS})