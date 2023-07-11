# Stacks and Queues

## introduction and what is the Stacks and Queues

- stacks and queues are linear data struectures to store a collection of elements.
each of them has own rules to add, remove elements to determine which elements are accessed.

    

### Advantages why we use Stacks and Queues:

The advantages of using dtack and queues consider as following :

- simplicity : stacks and queues have a simple operations which maiking them easy to understand and to deal with.

- Efficieny : stacks and queues have a fast time on run becuase they have a constant time complexity for these operations like insertion and deletion, enqueuing and dequeuing.

- Problem-solving : stacks and queus has an effictive on most of programming problems.

- Memory managment : stacks are useful in managing function calls, recursions, and memory allocation. while the queues are useful for handling requests, shceduling, and resource allocations.


### what is the Stacks and Queues 

- Stack : is a last in first out (LIFO) data structure, in simple word means that the last element you will add it will be the first element you will remove. simple example a stack of plates.

- queue : is a First In First Out (FIFO) data structure, in simple word that means the first element you gonna add to the queue will be the first element you will remove. simple example line of people on resturant the first will come who is the first will be served.

### How to use Stacks and Queues 

## Stack : 

- ### Choose an implementation :

    -  if i want to use the stack i have to determine what the implementation i want to use, like array  or linked list.

- ### push :

    - if we want to add an element to the stack we use push method to add to the last of the stack or the top of the stack
    - we creating a node and passing a value to it and then we will set the next node to the the current top of the stack.
    - and then we have to update the top of the stack to point on the new node we created.

- ### Pop : 

    - if we want to remove a node from the stack we will remove from the end or the top of the stack.
    - we will retrieve the value of the top node or element and updating the the top to point to the next node.

- ### peek : 
    - if we want to view the the value of the top element without removing it.

- ### isempty : 
    - to check if the stack is empty or not
    - return `true` if the top not null or `false` if the top node is `NULL`

## Queue :

- ### Choose an implementation :

    - if i want to use the queue i have to determine what the implementation i want to use, like array  or linked list.

- ### Enqueue : 

    - if we want to add an element or node to the queue we have to use the enqueue operation
    - so we have to create a node or element to contain the value we want to add
    - set the new node's next reference to null or the rear reference.
    - updating the rear reference of the queue to point on the new node.

- ### dequeue : 

    - the remove is will be from the front we have to use the dequeue operation.
    - retrive the value of the front node of the queue.
    - updating the front reference to the queue to the next node

- ### peek : 
    - if we want to view the the value of the front element element without removing it.

- ### isempty : 

    - to check if the queue is empty or not.

    - return `true` if the front node not null or `false` if the front node is `NULL`



### types of Stacks and Queues

- ## stacks : 
    - Array-based stack
    - linked-list-based stack 
    - Dynamic stack : Automaticaly resizes itself when it needed. 

- ## queues : 

    - Array-based Queue 
    - linked-list-based Queue
    - Priority queue : assigns a priority to each element and dequeues based on priority.
    - circular queue : uses a circular array to efficiently utilize the memory.

### example of Stacks and Queues 

## Stack Example:
Suppose you want to reverse a word using a stack. You can push each character of the word onto the stack and then pop them out to get the reversed word.

## Queue Example:
Suppose you want to simulate a print job queue. You can enqueue print jobs (documents) into the queue, and the printer will dequeue and print them one by one in the order they were added.


### Quiz For Any one want to answer 

- What is the main difference between a stack and a queue?
        - a) Stacks follow the FIFO (First In, First Out) rule, while queues follow the LIFO (Last In, First Out) rule.
        - b) Stacks follow the LIFO (Last In, First Out) rule, while queues follow the FIFO (First In, First Out) rule.
        - c) Stacks and queues follow the same rule of operation.
        - d) Stacks and queues have no specific rule of operation.

- Which operation adds an element to the top of a stack?
    - a) Push
    - b) Pop
    - c) Enqueue
    - d) Dequeue

- What is the time complexity for the push operation in a stack?
    - a) O(1)
    - b) O(log n)
    - c) O(n)
    - d) O(n^2)

- In a queue, which operation removes an element from the front?
    - a) Push
    - b) Pop
    - c) Enqueue
    - d) Dequeue

- What data structure is commonly used to implement a stack or a queue?
    - a) Array
    - b) Linked List
    - c) Hash Table
    - d) Tree

- Which of the following is an example of using a stack?
    - a) Evaluating a mathematical expression
    - b) Simulating a print job queue
    - c) Implementing a cache system
    - d) Managing a waiting list for a restaurant

- Which of the following is an example of using a queue?
    - a) Reversing a string
    - b) Undo/Redo functionality in a text editor
    - c) Checking for balanced parentheses in an expression
    - d) Traversing a binary tree

Answers:

- b) Stacks follow the LIFO (Last In, First Out) rule, while queues follow the FIFO (First In, First Out) rule.
- a) Push
- a) O(1)
- d) Dequeue
- b) Linked List
- a) Evaluating a mathematical expression
- b) Undo/Redo functionality in a text editor

#### Test Your Knowledge. 

## Things i want to know more About 

- How to start dealing with stakcs and queues indise the C#.
- And how to make a method inside it and how to use it as a first choice in some problem sovling programming solutions.