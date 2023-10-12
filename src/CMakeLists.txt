add_library(hand STATIC hand_index.c deck.c)
target_link_libraries(hand PRIVATE m)
target_include_directories(hand PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})