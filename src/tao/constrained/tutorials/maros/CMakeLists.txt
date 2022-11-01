add_executable (maros maros.c)
target_include_directories (maros PUBLIC ${PETSC_INCLUDE_DIR})
target_link_libraries (maros LINK_PUBLIC ${PETSC_LIBRARIES} /usr/local/superlu_dist-8.1.1/lib/libsuperlu_dist.so)

