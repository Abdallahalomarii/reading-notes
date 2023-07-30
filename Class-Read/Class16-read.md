## DTO class 16 read

-  DTOs are objects used to transfer data between different layers of an application. They act as containers for data and are mainly used to pass data from a data access layer to a presentation layer or vice versa. One of the main benefits of using DTOs is that they help in reducing the amount of data sent over the network, which can improve the performance of our application.

- To use DTOs effectively, we need to follow a few guidelines. Firstly, we should keep our DTOs simple and only include the necessary data that needs to be transferred. It's important not to overload them with irrelevant information.

- Another key point is that we should avoid making changes to DTOs frequently. Since DTOs are often used by different layers of an application, making frequent changes to them can lead to compatibility issues and make our code harder to maintain.

- In C# ASP.NET, we can create DTOs as plain classes with properties that represent the data we want to transfer. We can then use mapping techniques to convert our domain model objects to DTOs and vice versa. AutoMapper is a popular library that can help us with this mapping process.

-  we excluded the property from the DTO Class to avoid sending sensitive data over the network unnecessarily.