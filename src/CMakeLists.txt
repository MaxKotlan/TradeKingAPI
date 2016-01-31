#build executable
include_directories(${CMAKE_SOURCE_DIR}/include)
include_directories(${CMAKE_SOURCE_DIR}/extern/cpp-netlib)
include_directories(${Boost_INCLUDE_DIR})
add_library(libtradeking Request.cpp)
