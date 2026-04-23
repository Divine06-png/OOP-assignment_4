Name: Divine Phillip
Course: Object Oriented Programming(C++)
Registration Number: 2420011

**Assignment overview**
This assignment consists of three separate C/C++ programming problems that demonstrate fundamental concepts:

1. Person Class with Swap Function - A class implementation with member functions, getters, and a friend function to swap
   object data.

3. Dynamic 2D Seat Map - A 10×10 seat arrangement system using dynamic memory allocation, memset, memcpy, and proper memory
   management.

4. String List Dictionary - A word storage system with dynamic string allocation, search, modification, and deletion operations.

**Program Description**
**Problem 1: **
A simple Person class that stores a student's name, ID, and age. The program demonstrates:

*Object initialization using an init() method
*Printing formatted student information
*Getter methods for private member access
*Swapping all data between two Person objects using a friend function

**Problem 2: **
A seat arrangement system for a 10×10 venue using a dynamically allocated 2D integer array. Features include:

*Dynamic allocation of a 10×10 array using malloc
*Initialization to zero using memset
*Predefined seat assignments (student ID last two digits)
*Backup creation using row-by-row memcpy
*Row clearing operation (row 5 set to all zeros)
*Finding the row with the most assigned seats (non-zero values)
*Complete memory deallocation at program end

**Problem 3: **
A dynamic word storage system that manages up to 5 words with individual memory allocation per string. Operations include:

*Storing initial words: "alpha", "bravo", "charlie", "delta", "echo"
*Searching for a word and returning its index
*Modifying a word at a specific index ("bravo" → "blueberry")
*Deleting a word and shifting remaining elements
*Memory cleanup for all allocated strings
