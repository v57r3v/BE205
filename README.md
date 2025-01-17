java cHomework 2: experiments with data 
structures for searching 
 
BE205 2024 MUST 
Overview 
We have learned several data structures that can support data storage and searching, including: 
AVL tree (self-balancing binary search tree)
Hash table
Binary Heap (priority queue). 
In this homework, we will write a C/C++ program to use these data structures. More exactly, your 
program should accomplish the following tasks: 
Tasks 
Part 1: Read the words from a file to a linked list 
 A token is a sequence of letters. For example for the sentence: 
That I could make those people dance, 
And maybe they'd be happy for a while. 
The sequence of words, described here as a string marked by double quotes, will be : 
"That" "I" "could" "make" "those" "people" "dance" "And" "maybe" "they" "d" "be" "happy" 
"for" "a" "while"
 
 Open an input file message.txt (provided with this homework). It includes a paragraph of the 
lyrics of the song "American Pie" and an English article excerpt from the book "Tractatus LogicoPhilosophicus"
 written by the philosopher Ludwig Wittgenstein. 
 
Read the sequence of words into a linked list 
Each node of the linked list should contain a string, which is the word. 
You can choose to use a C-string or a C++ string object. 
Do not use some library of linked lists. The nodes should be defined in your code. 
Hint: The provided code for reading a word can be useful. 
 
Print the words in the linked list. Maybe something like :
 1) That  2) I  3) could  4) make  5) those  6) people  7) 
dance  8) And  9) maybe  10) they  11) d  12) be  13) happy  
14) for  15) a  16) while You can design the printing visual effect. 
Part 2 AVL Tree Construction 
 
Insert the words in list (built in task 1.2) one by one into an AVL Tree
Each node in the tree should store:
A distinct word (case ignored, e.g., "The" is the same as "the").
The count of occurrences of the word.
Nodes are ordered alphabetically by the word (dictionary order).
 
Print the tree. 
Hint: the provided the helpful code of printing a tree can be useful. 
 
Print the words (with their occurrence number) in the tree, in ascending dictionary order. 
Hint: using some traversal on the tree. 
Part 3 Hash Table 
Task 3.1 
Build a Hash代 写BE205、C/C++
代做程序编程语言 table. Insert the words of the list of task 1.2, one by one, into the list. Here are some 
requirements: 
Each item in the hash table should be a pair  , So, when trying to insert a 
word again into the table, its count should increase. 
The programmer can choose 
the size of the hash table (array size).
a collision resolution strategy (separate chaining, linear probing, or quadratic probing).
Task 3.2 
Search on the hash table 10 words that are in the input file. Also, seach 5 words that are not 
in the input file
When a word is found, print the word together with its count. 
When a word is not found, print a message like "The word is not found".
The printing result could be like: Part 4 : Binary Heap 
 
Build a binary heap where each node stores a pair  . Here are some description
The order between two pairs is defined as follows:
 is less than  if 
count1  
Print the  pairs on the heap in an ascending order (the order is defined above). 
Hint: Just pop the items from the binary heap and print them individually. 
 
Submission 
A most three students can form a group to do the assignment together. Only one student in 
the group needs to submit the homework. 
The files to be submitted on Moodle include: 
A .zip file containing all the source code files of your program.
Proper modularization by dividing your program into multiple files is encouraged. 
Putting all code in one text file is not good for this assignment. 
A text report file. The format can be (.docx, pdf, etc.). The file should describe 
What tasks have you accomplished? What are the remaining problems? 
The cooperation and workload sharing among the members of the group. 
Anything you want to describe, like the troubles you met and how you dealt with 
the problems. 
For the submission deadline, see the setting of this homework on the Moodle webpage. 
 
Search: facts       Found, Count: 3
Search: picture     Found, Count: 2
Search: logical     Found, Count: 2
Search: world       Found, Count: 2
Search: truth       Found, Count: 1
Search: representation Found, Count: 1
Search: philosophy   Not found
Search: language     Not found
Search: model       Found, Count: 1
Search: science     Not found
...

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
