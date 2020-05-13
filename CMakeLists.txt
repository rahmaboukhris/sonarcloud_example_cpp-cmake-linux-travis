cmake_minimum_required(VERSION 2.8)

file(GLOB src
    "*.h"
    "*.cpp"
)

add_executable(helloworld ${src})
