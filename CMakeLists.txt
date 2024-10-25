# CMake minimum version required
cmake_minimum_required(VERSION 3.10)

# Project name and version
project(RayTracingExample VERSION 1.0)

# Specify C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Set the output directory for binaries
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

# Add your source files
set(SOURCES
    src/main.cpp
)

# Create the executable from the source files
add_executable(${PROJECT_NAME} ${SOURCES})
