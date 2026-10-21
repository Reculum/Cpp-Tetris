
cmake_minimum_required(VERSION 3.15)

project(CppTetris CXX)

set(CMAKE_CXX_STANDARD 17)

set(CURSES_NEED_NCURSES TRUE)
find_package(Curses REQUIRED)

add_executable(Tetris ./main.cpp ./classe_griglia.cpp ./classe_matrice.cpp ./classe_tetramino.cpp ./funz_array.cpp ./funzioni_di_gioco.cpp ./liste.cpp)

target_include_directories(Tetris PRIVATE ${CURSES_INCLUDE_DIR})
target_link_libraries(Tetris PRIVATE ${CURSES_LIBRARIES})
