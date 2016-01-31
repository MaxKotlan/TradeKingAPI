#build executable
include_directories(${CMAKE_SOURCE_DIR}/src)
add_executable(example1 example1.cpp)
#target_link_libraries(example1 ${CMAKE_LIBRARY_OUTPUT_DIRECTORY}/libtradeking.a)
