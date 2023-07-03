# Enums

- the Enum is a value type defined by a set of named constants of the underlying integral numeric type. to define the enum we use th `enum` keyword and then we specifiy the name of this enum.
- after each variable name in the enum we have to sperate them in the block by `,`
- by default the values will be int and start from 0 and increasing. 
- we can add a the data type for the enum by adding `:` after the name following with number data type like ushort. 
- we can assign a value for the variables inside the enums.


# Collections 

- collections provide more flexible way to work with groups of objects. not like the array because the group you work with may shrink and grow dynamic through the application. 
- we can assign some key for the objects we have in the collections and we can quickly retrieve object by using the key.
- A collection is a class, so you must declare an instance of the class before you can add elements to that collection.
- If your collection contains elements of only one data type, you can use one of the classes in the `System.Collections.Generic` namespace. A generic collection enforces type safety so that no other data type can be added to it. When you retrieve an element from a generic collection, you do not have to determine its data type or convert it.
```bash 
    var animals = new List<string>();
    salmons.Add("Tiger");
    salmons.Add("Lion");
    salmons.Add("Duck");
    salmons.Add("Eagle");
    foreach (var animal in animals)
    {
        Console.Write(animal + " ");
    } 
    // Output: Tiger Lion Duck Eagle
```

- we can use foreach or we can for loops and both of them works.

- we can remove at and append from the collection

- we have more than one of the collections from the `System.Collections.Generic` : (`Dictionary<TKey,TValue>`: i remember we use it in firestore , `List<T>`, `Queue<T>`, `SortedList<TKey,TValue>`, `Stack<T>`).

- The classes in the System.Collections namespace do not store elements as specifically typed objects, but as objects of type Object.
and for the `system.Collections` namespace we have (`ArrayList`, `HashTabel`,`Queue`,`Stack`).

## Things i want to know more about is : 

- know all collections type.
- dealing more with the collections type
like adding, removing elements etc..
