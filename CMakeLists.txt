cmake_minimum_required(VERSION 3.19)
project(waifu C)

set(CMAKE_C_STANDARD 99)

add_executable(waifu_runner core/runner.c example/example_test.c)