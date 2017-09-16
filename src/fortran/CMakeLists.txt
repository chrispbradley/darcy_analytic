add_executable(darcy_analytic_fortran darcy_analytic.F90)

target_link_libraries(darcy_analytic_fortran PRIVATE opencmisslibs mpi)

install(TARGETS darcy_analytic_fortran DESTINATION bin)
