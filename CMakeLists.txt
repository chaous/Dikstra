cmake_minimum_required(VERSION 3.19)
project(Dikstra C)

set(CMAKE_C_STANDARD 11)

add_executable(Dikstra main.c dijkstra.c dijkstra.h matem.c matem.h queue.c queue.h stack.c stack.h tree.c tree.h)