project(tcp_client)
cmake_minimum_required(VERSION 3.16)

add_executable(tcp_client main.cpp)
target_link_libraries(tcp_client PRIVATE ${USED_LIBS})