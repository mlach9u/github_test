cmake_minimum_required (VERSION 3.8)

project(helloworld)

add_executable(helloworld
    main.cpp
)

enable_testing()

add_test(NAME helloworld COMMAND helloworld)
