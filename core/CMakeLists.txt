project(core)

add_library(core STATIC
    src/prototype.cpp)

target_include_directories(core PUBLIC include)

target_precompile_headers(core PUBLIC include/pch.h)
