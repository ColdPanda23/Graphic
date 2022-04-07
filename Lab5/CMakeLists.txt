cmake_minimum_required (VERSION 3.7)
project (GK_Lab5)

find_package(OpenGL REQUIRED)
find_package(GLUT REQUIRED)

add_executable(Lab5 lab4.cpp)

target_link_libraries(Lab5 PUBLIC OpenGL::GL GLUT::GLUT)