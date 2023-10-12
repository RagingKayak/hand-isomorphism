project(hand_isomorphism)

cmake_minimum_required(VERSION 3.22)

add_subdirectory(src)

add_executable(main ./src/check-main.c)
target_link_libraries(main hand)
