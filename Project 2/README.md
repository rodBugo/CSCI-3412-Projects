# CSCI 3412 Project 2 - Searching Algorithms

For this project we had to analyze and implement three different search algorithms. The report
will include static analysis of the algorithms – based on the written pseudo-code – as well as analysis of the
performance of the algorithms – based on the execution of the code. We were given an input file, wordlist.txt, that 
contains the complete works of Shakespeare with a single word or punctuation per line as well as blank lines where 
they appear in the text. A string is considered to be a word if the first character is alphabetic, although characters 
like hyphens and quotes may occur within a word. [This isn’t perfect, but it is simple to implement and will ensure 
everyone uses the same rules and gets the same counts.] Convert each word to lowercase to ensure that differences in 
case don’t lead to different words. It is only the words we are interested in – that is, don’t add punctuation to the
concordance.


Some constraints were to select and implement search algorithms to create the concordance based on the
following data structures.
1. Unsorted sequence (vector or list)
2. Sorted sequence (vector or list)
3. Hash table
