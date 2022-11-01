add_executable (ex1 ex1.c)
target_include_directories (ex1 PUBLIC ${PETSC_INCLUDE_DIR})
target_link_libraries (ex1 LINK_PUBLIC ${PETSC_LIBRARIES} /usr/local/superlu_dist-8.1.1/lib/libsuperlu_dist.so)

