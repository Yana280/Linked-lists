# Linked-lists
This code defines a singly linked list structure using a node structure in C. The structure contains an integer value and a pointer to the next node in the list.

The printLinkedlist function takes a pointer to the head node of the list as an argument and prints the integer value of each node in the list using a while loop that continues until it reaches the end of the list.

In the main function, three node pointers are defined, and each is allocated memory using malloc to create a new node. The integer value of each node is then set to 1, 2, and 3, respectively.

The nodes are then linked together by setting the next pointer of each node to the next node in the list, starting with the next pointer of the first node (one) to point to the second node (two), and so on.

Finally, the head pointer is set to the first node (one), and the printLinkedlist function is called with the head pointer as an argument to print the entire linked list.
![Screenshot (303)](https://user-images.githubusercontent.com/125993593/234577033-8c1ca57e-b7d5-416c-9ea0-9e1aa38ed838.png)

## Algorithm
start

Define a structure for a node that contains an integer value and a pointer to the next node.

Define a function printLinkedlist that takes a pointer to the head node of the linked list as an argument and prints the integer value of each node in the list using a while loop that continues until it reaches the end of the list.

In the main function:
Declare pointers for the head node and three additional nodes (one, two, and three).

Allocate memory for each of the three nodes using malloc.


Set the integer value of each node to 1, 2, and 3, respectively.

Link the nodes together by setting the next pointer of each node to point to the next node in the list.

Set the head pointer to the first node (one).

Call the printLinkedlist function with the head pointer as an argument to print the entire linked list.

stop
