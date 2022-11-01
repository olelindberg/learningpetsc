cmake_minimum_required(VERSION 3.24)
project (LearningPetsc)

list (APPEND CMAKE_MODULE_PATH "${LearningPetsc_SOURCE_DIR}/cmake-modules")

find_package (PETSc REQUIRED)
message (STATUS "PETSC COMPILER ${PETSC_COMPILER}")

add_subdirectory (src)

