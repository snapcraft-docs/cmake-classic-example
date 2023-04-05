cmake_minimum_required(VERSION 3.10)
project(CMakeSnapProject)
add_executable(cmake-example main.cxx)
install(TARGETS cmake-example
        DESTINATION bin)
