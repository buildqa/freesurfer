add_test_executable(mrishash_find_test mrishash_test_100_find_tests.c)
target_link_libraries(mrishash_find_test utils)

add_test_executable(mrishash_intersect_test mrishash_test_200_intersect.c)
target_link_libraries(mrishash_intersect_test utils)
