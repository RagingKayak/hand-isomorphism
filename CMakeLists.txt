project(hand_isomorphism)

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")

cmake_minimum_required(VERSION 3.22)

add_subdirectory(src)

add_executable(main ./src/check-main.c)
target_link_libraries(main hand)
