Trie Data Structure Implementation

Author: Devon Villalona
Date: 4/18/2024

Description:
This program implements a Trie data structure in C. A Trie is a tree-like data structure used for storing a dynamic set of strings. It supports efficient insertion and lookup operations on strings.

Files:
1. main.c - Contains the main program logic, including Trie implementation, word insertion, and word lookup.
2. dictionary.txt - Input file containing a list of words to populate the Trie structure.
3. readme.txt - This file, providing information about the program.

Compilation Instructions:
To compile the program, use any C compiler such as gcc:
gcc -o trie main.c

Usage:
1. Ensure that the dictionary.txt file is present in the same directory as the executable.
2. Run the executable:
./trie
3. The program will read the dictionary file, construct a Trie data structure, and then perform a sample lookup operation to demonstrate the functionality.

Sample Output:
The program will display the occurrences of a few sample words in the dictionary, as well as deallocate the Trie structure at the end.

Dependencies:
This program relies on the standard C libraries: stdio.h, stdlib.h, and string.h.

