## interfaces 
- An interface in C# is a way to define a group of related functionalities that a non-abstract class or struct must implement. It provides a contract that specifies the methods, properties, events, and indexers that a class or struct implementing the interface must have.
- The interfaces can inherit from one interface or more than one and all member and events and methods will be inherit to the interface. 
- By using interfaces, you can, for example, include behavior from multiple sources in a class. That capability is important in C# because the language doesn't support multiple inheritance of classes. In addition, you must use an interface if you want to simulate inheritance for structs, because they can't actually inherit from another struct or class.
- Interfaces enable polymorphism in C#. You can create variables of an interface type and assign objects of different classes implementing that interface to those variables. This allows you to treat objects of different classes uniformly based on the common interface they implement.

## What problem does the interface solve?
- The basic problem an interface is trying to solve is to separate how we use something from how it is implemented.

## Why do we want to separate the use from the implementation?
- we can write code that can work with a variety of different implementations of some set of responsibilities without having to specifically handle each implementation.

- **Interfaces are trying to solve a very specific problem by allowing us to interact with objects based on what they do, not how they do it.**

 