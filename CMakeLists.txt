cmake_minimum_required(VERSION 3.10)
project(ci_test LANGUAGES C)

add_executable(ci_test src/main.c)

install(TARGETS ci_test RUNTIME DESTINATION bin)
