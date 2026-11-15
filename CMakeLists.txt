
cmake_minimum_required(VERSION 3.20)

project(AlgoStudy
    VERSION 1.0
    LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(algostudy
    backend/main.cpp
    backend/routes.cpp
    backend/algorithms/sorting.cpp
    backend/algorithms/searching.cpp
    backend/models/record.cpp
    backend/structures/linked_list.cpp
)
