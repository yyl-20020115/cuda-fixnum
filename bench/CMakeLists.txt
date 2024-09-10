add_executable(bench bench.cu)
target_link_libraries(bench fixnum_array fixnum functions modnum)
