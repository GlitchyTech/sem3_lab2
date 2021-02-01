cmake_minimum_required(VERSION 3.17)
project(sem3_lab2)

set(CMAKE_CXX_STANDARD 14)

add_executable(sem3_lab2 ArraySequence.hpp BST.hpp Dictionary.hpp DynamicArray.hpp Histogram.hpp interface_lab2.hpp
        main.cpp LinkedList.hpp ListSequence.hpp my_sorts.hpp Search_often_sub.hpp Sequence.hpp SortedSequence.hpp
               Sparce_vector.hpp test_BST.hpp test_dictionary.hpp test_histogram.hpp test_search_often_sub.hpp
               test_sorted_seq.hpp test_sorts.hpp test_sparce_vector.hpp)