# CMakeList.txt : Top-level CMake project file, do global configuration
# and include sub-projects here.
#
cmake_minimum_required (VERSION 3.8)

project ("FileRex")


# Add source files to the project
add_executable(file-o-saurus-rex 
    src/main.cpp 
    src/files.cpp
    src/tui.cpp
)

# Include header files
target_include_directories(file-o-saurus-rex PRIVATE include)

