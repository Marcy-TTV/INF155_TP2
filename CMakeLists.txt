cmake_minimum_required(VERSION 4.3)
project(INF155_TP2 C)

set(CMAKE_C_STANDARD 11)

add_executable(INF155_TP2 main.c
        commande.c
        interface.c
        fichiers.c
        lecture.c
        simulation.c)
