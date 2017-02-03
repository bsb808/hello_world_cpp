cmake_minimum_required(VERSION 2.8.3)
project (hello_world_cpp)

# Set destination directories 
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/lib)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_SOURCE_DIR}/bin)

include_directories(include)

set(SOURCES 
  src/${PROJECT_NAME}.cpp
)

add_executable(${PROJECT_NAME} ${SOURCES})