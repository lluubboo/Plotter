# Set the minimum required version of CMake
cmake_minimum_required(VERSION 3.12)

# Set the project name
project(Plotter)

# Add the source files for the library
set(SOURCES
    src/file1.cpp
    src/file2.cpp
)

# Create the static library target
add_library(Plotter STATIC ${SOURCES})

# Set the include directories for the library
target_include_directories(Plotter PUBLIC include)
