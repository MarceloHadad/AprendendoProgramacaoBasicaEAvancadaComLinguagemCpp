cmake_minimum_required(VERSION 3.12.0)

project(tarefa_1)

add_executable(tarefa_1)

target_include_directories(tarefa_1 PRIVATE)

target_sources(tarefa_1 PRIVATE
    tarefa_1.cpp)