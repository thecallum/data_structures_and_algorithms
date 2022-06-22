# Section 2 - Arrays and Big-O Notation

## What is Time Complexity?

The number of steps involved.

## What is Memory Complexity?

The amount of RAM used.

## What is Big O?

Big O describes the complexity of your code using algebraic terms.

## What are the 5 main Big O Notations?

- O (1) - Constant
- O (log n) - Logarithmic
- O (n) - Linear
- O (n log n) - Loglinear
- O (n^^2) - Quadratic

## How does the Array data type work?

Arrays are contiguous blocks in memory (not scattered). This is why you cannot resize an array.

Therefore, if an array starts at memory address X, and the size of each element is Y.

We can calculate the memory address of I element using `X + I x Y`.

Arrays are good for retrieving information if you know the index.

## What are the 7 main array operations?

| **Operation**               | **Notation** |
|-----------------------------|--------------|
| Retrieve with index         | Constant     |
| Retrieve without index      | Linear       |
| Add element to full array   | Linear       |
| Add element to end of array | Constant     |
| Insert or update at index   | Constant     |
| Set index to null (delete)  | Constant     |
| Delete elements by shifting | Linear       |