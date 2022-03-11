cmake_minimum_required (VERSION 3.2)
project (cpp_learning)

if(MSVC)
add_compile_options(/W3 /MP)
else()
add_compile_options(-W -Wall -fPIC)
endif()

add_subdirectory (src)