- ### Purpose of Entity Framework:

    - Entity Framework is an object-relational mapper (ORM) that enables developers to work with databases using object-oriented programming (OOP)      concepts.
    Its purpose is to simplify database interactions by allowing developers to work with database entities as objects, abstracting away the underlying SQL queries.

- ### Code First Migration:

    - Code First Migration is a technique in Entity Framework that allows developers to create and modify database schemas using code.
    Instead of designing the database schema first and then generating code, you define your entities and relationships in code, and Entity Framework generates the corresponding database schema.

- ### Seeding Data:

    - Seeding data refers to the process of populating the database with initial data during its creation or migration.
    In Entity Framework, you can use data seeding to insert predefined records into database tables, ensuring that your application has some initial data to work with.

- ### Representing Composite Key Relationships in MVC Core:

    - A composite key relationship is when a table's primary key consists of multiple columns.
    In MVC Core, you can represent composite key relationships by using the Fluent API, which allows you to configure entity relationships in a more flexible and explicit manner.
    
    By overriding the OnModelCreating method in your DbContext class, you can define composite keys using the HasKey method and configure relationships between entities using the HasOne and WithMany methods.

- ### MVC with EF: 

    - The ASP.NET Core framework includes built-in support for the Entity Framework, which makes it
    easy to work with relational databases using object-oriented programming concepts such as classes and objects.

    - Model-View-Controller (MVC) is a design pattern commonly used in web development.
    When using Entity Framework with MVC, the Model represents the data entities, the View handles the user interface, and the Controller manages the interactions between the Model and the View.
    
    - To get started, developers need to set up the Entity Framework data context, define entity classes, and create controllers and views to handle CRUD (Create, Read, Update, Delete) operations.