# set minimum cmake version
cmake_minimum_required(VERSION 3.5 FATAL_ERROR)

# project name and language
project(chapter-01 LANGUAGES C)

if (WIN32)
elseif(UNIX)
    add_executable(fd_seri fd_seri.c)
else()
endif()

