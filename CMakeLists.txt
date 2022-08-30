cmake_minimum_required(VERSION 3.10)
project(RecurseDir)
add_executable(RecurseDir main.cpp)
target_compile_features(RecurseDir PRIVATE cxx_std_17)