include_directories(include)
file(GLOB sources ${PROJECT_SOURCE_DIR}/src/*.cc)
add_executable(program main.cpp ${sources})



