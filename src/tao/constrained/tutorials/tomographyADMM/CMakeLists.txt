add_executable (tomographyADMM tomographyADMM.c)
target_include_directories (tomographyADMM PUBLIC ${PETSC_INCLUDE_DIR})
target_link_libraries (tomographyADMM LINK_PUBLIC ${PETSC_LIBRARIES} /usr/local/superlu_dist-8.1.1/lib/libsuperlu_dist.so)

