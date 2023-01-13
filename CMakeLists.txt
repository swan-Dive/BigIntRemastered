project(my_bigint)

set(SOURCES main.cpp)
include_directories("header")
add_subdirectory(src)
add_executable(bigint ${SOURCES})
target_link_libraries(bigint bigdoublelib)
target_link_libraries(bigint bigintlib)

