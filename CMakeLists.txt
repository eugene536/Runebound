cmake_minimum_required(VERSION 3.10)

project(Runebound CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

set(SDL2_INCLUDE_DIR C:/cpplibs/SDL2/x86_64-w64-mingw32/include/)
set(SDL2_LIB_DIR C:/cpplibs/SDL2/x86_64-w64-mingw32/lib/)

include_directories("include")

include_directories(${SDL2_INCLUDE_DIR})
link_directories(${SDL2_LIB_DIR})

add_executable(${PROJECT_NAME} src/graphics.cpp)

target_link_libraries(${PROJECT_NAME} ${SDL2_LIBRARY} -lmingw32 -lSDL2main -lSDL2 -mwindows -lSDL2_image)
