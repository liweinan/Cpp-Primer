cmake_minimum_required(VERSION 3.9)
project(cmake_clion)

set(CMAKE_CXX_STANDARD 17)

add_executable(ex1_1 ch01/ex1_1.cpp)
add_executable(ex14_07 ch14/ex14_07.h ch14/ex14_07.cpp ch14/ex14_07_TEST.cpp)

add_executable(ex7_01 ch07/ex7_01.cpp)
add_executable(ex7_02 ch07/ex7_02.h ch07/ex7_02.c)

add_executable(ex7_41 ch07/ex7_41_TEST.cpp ch07/ex7_41.cpp ch07/ex7_41.h)
add_executable(ex7_03 ch07/ex7_03.cpp ch07/ex7_02.h)
add_executable(ex10_06 ch10/ex10_06.cpp)
add_executable(ex10_07 ch10/ex10_07.cpp)