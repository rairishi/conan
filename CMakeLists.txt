PROJECT(MyHello)
cmake_minimum_required(VERSION 3.2.1)

add_library(hello src/hello.cpp)
add_executable(greet src/main.cpp)
target_link_libraries(greet hello)

