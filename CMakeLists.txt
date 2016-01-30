cmake_minimum_required(VERSION 3.0)
project(TradeKingAPI)

#output files to appropriate directories
set(CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/lib)
set(CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/lib)
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

#build extern libraries
add_subdirectory(extern)

#buld source
add_subdirectory(src)
