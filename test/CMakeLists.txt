project(test)
cmake_minimum_required(VERSION 2.8)

set(CMAKE_BUILD_TYPE Debug)


add_executable(${PROJECT_NAME} first_iteration_unit_tests.cpp)
target_link_libraries(${PROJECT_NAME}  LINK_PUBLIC mmemory-lib)


