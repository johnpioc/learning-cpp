cmake_minimum_required(VERSION 3.10)
project(learningcpp)

# Set C++ Standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Include projects and sandbox
add_subdirectory(sandbox)
add_subdirectory(projects/hypotenuse-calculator)
add_subdirectory(projects/cli-calculator)
