# CSCI 3412 Project 1 - Sorting Algorithms

For this program, we were tasked to select three (3) sorting algorithms to analyze and implement. The report should include a 
static analysis of the algorithms – based on the written pseudo-code – as well as analysis of the
performance of the algorithms – based on the execution of the code.
We were also given several input files that will allow us to analyze various aspects of the code. All the data are
integers between 1 and 100 inclusive and you will be given the following data sets:
1. shuffled.txt – the integers 1-100 in random order – i.e., shuffled
2. sorted.txt – the integers 1-100 in sorted order (ascending order)
3. nearly_sorted.txt – the integers 1-100 in nearly sorted order
4. unsorted.txt – the integers 1-100 in unsorted order (descending order)
5. nearly_unsorted.txt – the integers 1-100 in nearly unsorted order
6. duplicate.txt – 100 integers 10, 20, …, 100 – i.e., many duplicates – in random order
7. one_million_randoms.txt – 1,000,000 integers 1-100 in random order

The only constraints were that the first algorithm must have an expected
running time that is 𝑂(𝑛^2) – i.e. a naive sorting algorithm like bubble sort or selection sort. The second
algorithm must have an expected running time that is 𝑂(𝑛 lg 𝑛) – the ‘normal’ rate of growth for
comparison sorts like merge sort or quick sort. The third sort algorithm must have an expected running
time that is 𝑂(𝑛), which is only possible for non-comparison-based sorts where we know – and take
advantage of – some aspect of the data that allows us to avoid comparing the elements to be sorted. [In
this case, the fact that all the values to be sorted are integers between 1 and 100 inclusive.]
