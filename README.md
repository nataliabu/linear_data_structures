# Linear Data Structures

Data structures are our friends! They help us organize, manage and storage
information.

A linear data structure has its data elements arranged as a sequence.

## Nodes

Nodes are the building blocks of many computer science data
structures.

A node has:

* Data
* Link(s) to other nodes

Since linear data structures are arranged as a sequence, each node can have only
one link connecting it to the next node (and optionally one link connecting it to 
the previous node).

[node.py](https://github.com/nataliabu/linear_data_structures/blob/main/node.py) is my implementation of nodes using python

## Linked Lists

A linked list is a linear data structure. Contrary to arrays, the elements of a
linked list are not stored in the memory in a contiguous location. Instead the
elements are linked using pointers.

This is very cool because it allows us to add, remove and re-order items easily.

[linked_lists.py](https://github.com/nataliabu/linear_data_structures/blob/main/linked_lists.py)
is my implementation of linked lists using python (using also my implementation
of nodes)

## Stacks

Another useful data structure is the stack. Stacks in computer science work
pretty simmilar to stacks or piles in real life. In fact, in a wonderful zine
called [Hip Hip Array!](https://shop.bubblesort.io/products/hip-hip-array) they
say they are sure stacks are called after a stack of pancakes :)

A stack follows a last in, first out (LIFO) principle.

[stack.py](https://github.com/nataliabu/linear_data_structures/blob/main/stack.py)
is my implementation of stacks using python (using also my implementation of
linked lists (using also my implementation of nodes))

