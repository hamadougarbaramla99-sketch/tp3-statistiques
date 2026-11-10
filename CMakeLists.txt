cmake_minimum_required(VERSION 3.20)
project(tp3_statistiques LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(statistiques
    src/version.cpp
    src/regles.cpp
    src/saisie.cpp
target_include_directories(statistiques PRIVATE include)
target_compile_options(statistiques PRIVATE -Wall -Wextra -Wpedantic)
