cmake_minimum_required(VERSION 3.13)
project(counting_valleys_test)

add_executable(counting_valleys_check ../counting_valleys_tests/counting_valleys_check.cpp)

target_link_libraries(counting_valleys_check gtest gtest_main)