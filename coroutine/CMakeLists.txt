project(coroutine)
cmake_minimum_required(VERSION 3.16)

add_compile_options("-fcoroutines")
add_executable(coroutine main.cpp)
target_link_libraries(coroutine PRIVATE ${USED_LIBS})