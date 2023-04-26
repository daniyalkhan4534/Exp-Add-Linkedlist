# Exp-Add-Linkedlist

A linear data structure called a linked list has a number of connected nodes. Each node keeps the data and the address of the node after it here. For instance, since you must begin someplace, we assign the initial node's address a unique name, HEAD. The linked list's final node can be distinguished since its next segment points to NULL.
There are three different forms of linked lists: single, double, and circular.

Representation of Linked List:-
Each node consists:

1.A data item
2.An address of another node


![image](https://user-images.githubusercontent.com/127819492/234479478-6574cc5c-2db7-461a-b7e6-3c493ad5fda2.png)

The power of a linked list comes from the ability to break the chain and rejoin it. E.g. if you wanted to put an element 4 between 1 and 2, the steps would be:


1.Create a new struct node and allocate memory to it.
2.Add its data value as 4
3.Point its next pointer to the struct node containing 2 as the data value.
4.Change the next pointer of "1" to the node we just created.
