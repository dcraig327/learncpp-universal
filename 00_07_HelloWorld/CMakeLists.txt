# CMakeList.txt : CMake project for 00_07_HelloWorld, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (00_07_HelloWorld "00_07_HelloWorld.cpp" "00_07_HelloWorld.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET 00_07_HelloWorld PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
