cmake_minimum_required(VERSION 3.10)
project(main)

# Spécifie que nous utilisons C++17
set(CMAKE_CXX_STANDARD 17)

# Ajoute l'exécutable, avec le nom de l'exécutable et le chemin vers le fichier source
add_executable(main main.cpp)
