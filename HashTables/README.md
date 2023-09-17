# Hash Tables

## What is the Hash Tables

- Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In
the case of a hashtable, it is used to determine the index of the array.

- Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value
pairs if a collision occurs.

- Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

## Why do we use the hash tables

- Why do we use them?
- Dictionary
- Library

- Hash tables are commonly used when you need fast access to data, especially in scenarios where you have a large dataset and want to avoid slow linear searches. They are used in databases, caches, and many other applications.

## How Does a Hash Table Work?

- ### Hash Function

  - The core of a hash table is a hash function. This function takes a key as input and produces an index in an array where the associated value will be stored. It should be deterministic, meaning that the same key will always produce the same index.

- ### Array

  - Hash tables use an array to store values. Each index in the array corresponds to a "bucket" that can hold multiple key-value pairs.

- ### Storing Data

  - To store data in a hash table, you apply the hash function to the key to determine the index where the value should be placed. If two different keys hash to the same index (a collision), most hash tables have strategies to handle this, such as chaining (each index holds a linked list of key-value pairs).

- ### Retrieving Data

  - When you want to retrieve a value, you apply the same hash function to the key to find the index, then look in that index's bucket for the value.

## Visual Example

- Imagine a hash table as a bookshelf with numbered slots. Each slot can hold multiple books. The books represent key-value pairs, where the key is the title of the book, and the value is the content of the book.

- Hash Function: The librarian uses a magic formula (the hash function) to decide which slot each book should go into based on its title.

- Storing Data: When you bring a new book to the library, the librarian calculates the slot number using the hash function and places the book there. If two books have the same title (a collision), the librarian creates a small bookshelf (linked list) at that slot to hold both books.

- Retrieving Data: When you ask for a book by its title, the librarian uses the same magic formula to find the slot and then looks on that shelf to find your book.
