# Specify the minimum version of CMake required
cmake_minimum_required(VERSION 3.10)

# Set the project name
project(SimpleCalculator)

# Set the C++ standard to use
set(CMAKE_CXX_STANDARD 11)

# Add an executable target named "simple_calculator" with the source file "main.cpp"
add_executable(simple_calculator main.cpp)
