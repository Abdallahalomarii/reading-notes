# Class 04 OOP 

- ## Class 
    - The `Class` is a reference type, when we create a reference it set to be null unless we make a an instance of the class with new operator. or assign it an object of compatible type in elsewhere
      - when we creating an object from the class this object can access all methods that class make it available to use in anywhere
      - the syntax of creating class is public class name then we can create methods inside it or fields or properties
      - to be noticed we create the class public to let any instance to access it.
      - we can use an object to make an instance from this class and access all methods inside the class.
      - syntax of creating object is ClassName objectName = new Classname() and also we can another objects copies this object.
      - on of the most benefit of the class is that we can initialize inside it a different types.
      - we have something called constructor we using it inside the class the main point of this thing is to setting an initial value.
      - so when we call the class by object instance we have to send value for the class and the constructor deal with them.
      - the final thing in class is the inheritance we use this OOP characteristics to inherit property or methods from class to class so one come to be the parent and one as a child.
      
---
- ## Constructors 
    - We know now what is the Constructor but let's take a deep look inside it. so first thing to be in mind when we call the class the first thing will be called the Constructor, Constructor consider under two types first one is the static constructor and the second one is instance constructor static will be run before any action and the instance will run after creating a instance of class.

---

- ## Properties 
    - A property is a member that provides a flexible mechanism to read, write, or compute the value of a private field. Properties can be used as if they're public data members, but they're special methods called accessors. This feature enables data to be accessed easily and still helps promote the safety and flexibility of methods. so we have an different level we can say, first one is the public which allows you to access it from any where, you can access the private in the same class or any related class (inheritance), read-only allow you to only retrieve data by the symbol =>.
    - the backing fields properties involves using get to retrieve data and set to perform data.
    - Required properties force user Client code to initialize any property or field.


    - What’s the difference between a static and an instance constructor? 
        - the Static Constructor is the initalizer of the static values and it's run before first instance called and it is not taking any parametr while the instance constructor it is exceuted when you create the new instance of type to specify that code.

    - How does the use of a static constructor differ from setting properties/values?
        - the static constructor is running for only one-time before any of class members accessed by any other instance. while setting properties/values it is specific to any other instance and allow you to assign more than one time.

    - Knowing what you now know about the stack and the heap, how might you rethink the way you did projects in previous courses, to make more effecient use of memory?
        - by using values types instead of using references types when it is possible to save memory, and reusing objects instead of creating new ones to reduce the memory allocation, I think by dispose any object that we are not using any more to free up the memory and optimize the data by using the correct data-structures and algorithms. 

    - Compare “Garbage Collection” in C# with the lifecycle of normal household items.
        - the Garbage collection it is a way to manage the code and free up the memory, by removing unnecessary codes and methods that we are not using it any more and it takes space in the memory. by comparing it in real life it is like how re cleaning the house from the garbage or unnecessary stuff that we have and not usable any more that allows us to get free spaces and get the house clean and ordered and have a lot of spaces and it is not full and you can find your things for example very fast you can search in your house for something where you know where is everything is setup before.t 
- inherit a class and using objects dealing with this symbol => creating a constructor and setting data to a class and get data from the class using the another data-structures algorithms that increase my code performance.