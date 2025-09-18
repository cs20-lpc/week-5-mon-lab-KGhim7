cmake_minimum_required(VERSION 4.0)
project(week_5_mon_lab_KGhim7)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(week_5_mon_lab_KGhim7
        DoublyList.hpp
        DoublyList.tpp
        driver.cpp
        List.hpp)
