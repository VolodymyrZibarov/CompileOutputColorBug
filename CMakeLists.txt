cmake_minimum_required(VERSION 3.16)

project(CompileOutputColorBug)

add_executable(${PROJECT_NAME}
    CommonHeader.h
    main.cpp
    OtherClass1.cpp OtherClass1.h
    OtherClass2.cpp OtherClass2.h
    )

target_compile_options(${PROJECT_NAME} PUBLIC -Wall)
