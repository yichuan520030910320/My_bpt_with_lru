cmake_minimum_required(VERSION 3.10)
project(bpt_with_lru)

set(CMAKE_CXX_STANDARD 14)

add_executable(bpt_with_lru main.cpp
        bplustree.hpp
        lru.h
        hashmap.h)