cmake_minimum_required(VERSION 3.8)
project(SERWER_PILKA_NOZNA_POLL)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp StanGry.cpp StanGry.h)
add_executable(SERWER_PILKA_NOZNA_POLL ${SOURCE_FILES})