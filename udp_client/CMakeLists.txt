project(udp_client)
cmake_minimum_required(VERSION 3.16)

add_executable(udp_client main.cpp)
target_link_libraries(udp_client PRIVATE ${USED_LIBS})