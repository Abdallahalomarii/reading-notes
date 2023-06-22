# Linked List

## introduction and what is the linked list
A linked list is a linear data structure, in which the elements are not stored at contiguous
memory locations. The elements of a linked list are connected using pointers/references to form a chain or
link.

### Advantages why we use Linked list:
- Dynamic memory allocation and deallocation can be done easily without any need for restructuring.
- Insertion and deletion operations take constant time O(1).
- Searching an element takes logarithmic time (O(n)) because we have to traverse
the entire list until it reaches that particular node where our required item resides.
- It supports random access as well since each node has its own address value.
- so it one of the most  flexibility  and efficient  data structure.

### what is the linked list 
A linked list is a data structure that consists of a sequence of nodes, where each node contains a value and a reference (or pointer) to the next node in the sequence.

### How to use Linked List 
Each node in linked list  contains  Value and the Next Pointer

where the value is the actual data or information stored in the node.

and the next pointer points towards another node which holds the link for further traversal.




### types of linked list 

1. Singly LinkedList : In singly linked lists , there are only two pointers - head 
& tail . The first element will have no previous elements while last element will not point any other element.
2. DoublyLinkedList:In doubly linked lists both prev &next links exist at
every node except the first one.
3. CircularLinkedlist: A circular linked list has its last node pointing back to itself so 
that it forms a circle.

### Operations on linked lists : 
1. Insertion
Operation: Inserting an item into a linked list means adding new nodes after some existing ones, without
changing their order.
2. Deletion
Operation: Removing items from a linked list is done by removing individual nodes or groups of them (a sub-list).
3. Searching : finding a specifc value in the list.

### example of Linked Lists 

so we have a train route where each word
represents a station and there are 
4 Stations 

The Train Route is : A -> B -> C -> D.

if i want to insert a station to the train route at the beginning  and delete the B station so the route will be like this : E -> A -> C -> D 

 ```bash 
           +-------+       +-------+      +-------+      +-------+
 beginning head -->  |  E     | -->  | A      | -->  |  C    | -->  | D      | -->  NULL
           +-------+       +-------+      +-------+      +-------+
              
``` 

### Conversations 

- E : Hey, I'm Node E! I have a value of 5 and my next pointer leads to Node A.
- A: Nice to meet you, Node E! I'm Node A, and I hold the value 100. My next pointer points to Node C.
- C: Nice to meet you, Node A! I'm Node C, and I hold the value 37. My next pointer points to Node D.
- D: Hello, Node1 and Node C! I'm Node D, with a value of 78. But guess what? My next pointer is NULL, indicating the end of the linked list.


### Quiz For Any one want to answer 

i got theses questions from the internet. 

- Linked lists are useful for handling _________ data structures.
- Inserting a new node involves updating the _________ pointer.
- Traversing a linked list requires following the _________ pointers.
- Deletion of a node requires updating the _________ pointer.
- Linked lists provide flexibility and efficiency in _________ and _________ operations.

Answers:
[the Answers of the quiz here ](#quiz-for-any-one-want-to-answer)
- dynamic
- head
- next
- next
- insertion, deletion


try to do not looking to theses answers. 

### Test Your Knowledge. 

## Things i want to know more About 

As Programmer i'm really intersted on the linked list and the methods of the linked list and the types i want to a deep learining inside it as i know it is very usefull and helpfuly for the code and the Time complixity which is one of the most data Structure alogratihm has a small Big o 