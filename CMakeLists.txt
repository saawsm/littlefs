cmake_minimum_required(VERSION 3.25)

project(littlefs LANGUAGES C)

add_library(littlefs STATIC
    "lfs.c"
    "lfs_util.c"
)

target_include_directories(littlefs PUBLIC .)
