# Project 4 : AVL
### Made for data structures course fall 2019

### Instructions I was given for this homework project (full PDF in files)
Attention!!! You will be using your BST tree or the BST code base I have provided for this project.
For this assignment you must implement an AVL which stores strings. Your AVL must implement all of
the basic operations we have talked about in class.

You should then write a program that allows a user to interact with an instance of the AVL you have
implemented. This program should implement a text-based interface that allows the user to:

1. Create an empty AVL. This should warn the user they are deleting the existing AVL and ask them
if they wish to proceed. Remind the user they can save the contents of their AVL to a file.
2. Insert a string into the current AVL.
3. Search for a string in the current AVL.
4. Remove a string from the current AVL.
5. Output the in-order traversal of the current AVL.
6. Output the pre-order traversal of the current AVL.
7. Output the post-order traversal of the current AVL.
8. Save the post-order traversal of the current AVL to a user specified filename.
9. Exit.

Make certain you inform the user of the available commands and any information pertaining to the
state of the system such as whether an AVL has been created, the number of nodes in the AVL, etc.
The BST and the AVL share lots of code in common. It would be wise to use your BST as a starting point
for implementing the AVL. I will provide you with a working BST code base, but not a working user
interface to make this easier.

Students who remember inheritance and are comfortable with inheritance might find implementing the
AVL as a subclass of the BST an easy way to prevent copy/paste issues. The use of inheritance is not a
requirement for this project.
