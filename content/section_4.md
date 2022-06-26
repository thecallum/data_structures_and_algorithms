# Section 4 - Lists

## What is a List?

The List (not arrays) is an abstract data type. 

- Do not dictate how the data is organised, but the operations that can be performed (interface),

## What are the 3 main List data structures?

- Array Lists
- Linked List
- Double Linked List

## What is an ArrayList?

An ArrayList is a non-generic collection that can store any and multiple different data types.

### Advantages

- Resizable (automatically)
- Elements can be added/removed at any index
- Can hold multiple different data types

## What is a Linked List?

A linked list is a linear data structure that stores data in a non-contiguous location (unlike an array). 

In a single linked list, each element contains a reference to the next. In a double-linked list, each element includes a reference to the next and previous.

### Methods (Single)

- AddFirst - `O(1)` constant
- RemoveFirst - `O(1)` constant
- Add/Remove index X - `O(n)` linear

### Methods (Double)

- AddFirst - `O(1)` constant
- RemoveFirst - `O(1)` constant
- AddLast - `O(1)` constant
- RemoveLast - `O(1)` constant
- Add/Remove index X - `O(n)` linear