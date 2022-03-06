cmake_minimum_required(VERSION 3.21)
project(filestructure_exercise)

set(CMAKE_CXX_STANDARD 14)
set (CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra ")

include_directories(.)
include_directories(FileStructureExercise)

add_executable(filestructure_exercise
        FileStructureExercise/FileStructureExercise.sln
        FileStructureExercise/FileStructureExercise.vcxproj
        FileStructureExercise/FileStructureExercise.vcxproj.filters
        FileStructureExercise/FileStructureExercise.vcxproj.user
        addition.h
        main.c
        multiplication.h
        subtraction.h)
