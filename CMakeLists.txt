cmake_minimum_required(VERSION 3.28)
project(zmk_config_original C)

set(CMAKE_C_STANDARD 11)

add_executable(zmk_config_original main.c
        config/corne.keymap)