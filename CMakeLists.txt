cmake_minimum_required(VERSION 3.17)
project(course_work C)

set(CMAKE_C_STANDARD 99)
#add_executable(course_work main.c)

set(RADIX_SORT _1_Radix_Sort/radix_sort.c)
add_executable(radix_sort ${RADIX_SORT})

set(BUCKET_SORT _2_Bucket_Sort/bucket_sort.c)
add_executable(bucket_sort ${BUCKET_SORT})

set(COUNTING_SORT _3_Counting_Sort/counting_sort.c)
add_executable(counting_sort ${COUNTING_SORT})