#build executable
include_directories(${CMAKE_SOURCE_DIR}/include)
add_library(libtradeking Market.cpp)
