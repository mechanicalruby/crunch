cmake_minimum_required(VERSION 3.31)
project(crunch)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# works for msvc ..
add_compile_definitions(_UNICODE)

file(GLOB CRUNCH_SRC "crunch/*.cpp")
add_executable(crunch ${CRUNCH_SRC})
