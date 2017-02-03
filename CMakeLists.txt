cmake_minimum_required(VERSION 2.8.3)
project (hello_world_cpp)

include_directories(include)

set(SOURCES 
  src/${PROJECT_NAME}.cpp
)

add_executable(${PROJECT_NAME} ${SOURCES})