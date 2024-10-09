project(playground-app)

add_executable(playground-app
    src/main.cpp)

target_include_directories(playground-app PRIVATE include)

target_link_libraries(playground-app PRIVATE core)
