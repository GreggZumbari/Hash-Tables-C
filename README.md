Assignment #4  Hash Tables

**Due by 11:59pm on Wednesday, 5/12/2021**

**Demo due by 11:59pm on Monday 5/26/2020**

This assignment is intended to be relatively straightforward. Hopefully it
will be easy for you, and boost your assignment grade!!!

You are given template code for hash_table.c and hash_table.h as well as a 
test program called test.c

You are only to turn in via Gradescope the updated hash_table.c code !

#1. (40pts) Write a subroutine to count the number of collisions for a hash table 
that has been filled. You are given a declaration of a function here: 

int hash_table_collisions(struct hash_table* hash_table);

Clearly, nothing is done yet. You are to loop through the array, then 
traverse the linked list, and count the number of collisions. 

#2 (40pts) Write an updated hash function. You are given a second hash function, called
``hash_function2()''. You are to change the code so that it is different from 
the hash_function1(). Initially, they are the same. 

Your code should confirm that the number of collisions, counted by the function you
wrote for part #1, should reduce.

The lowest number of possible collisions for 11 elements, and 8 slots is 3. To get full credit, the number of collisions should be less than 6 (so 5 or fewer) Be creative with your hash_functions!!! 

Note that both hash functions are passed to the hash_table code as a pointer to a function. Both functions are defined within hash_table.c, but only the second one is to be modified. 
