cmake_minimum_required (VERSION 3.7)
project (GK_Lab6)

find_package(OpenGL REQUIRED)
find_package(GLUT REQUIRED)

add_executable(Lab6 lab6.cpp)

target_link_libraries(Lab6 PUBLIC OpenGL::GL GLUT::GLUT)
target_link_libraries(Lab6 PRIVATE glu32)