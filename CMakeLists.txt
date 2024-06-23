cmake_minimum_required(VERSION 3.28)
project(zmk_config_original)

set(CMAKE_C11_STANDARD 14)

add_executable(zmk_config_original
        config/corne.conf
        config/corne.keymap
        config/west.yml
        zephyr/module.yml
        build.yaml)
