project(BigIntLibs)

add_library(bigintlib BigInt.cpp ../header/header.hpp)
add_library(bigdoublelib BigDouble.cpp ../header/header.hpp)
target_include_directories(bigdoublelib  PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
target_include_directories(bigintlib  PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})