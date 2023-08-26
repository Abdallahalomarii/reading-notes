# Class Read 26 || Intro to MVC
- ### Azure DevOps:
 - Azure DevOps is a set of development tools and services that enable teams to plan, develop, test, and deliver software efficiently. It includes features 
    like version control, build automation, release management. and it is also commonly used in team manmgent life cycle 

- ### MVC : 

    - is a design pattern or architecture which helps in developing the web application in a most efficient way when compared with the traditional ASP.NET  Web Application.

        - **Model** : layer represent the objects in our Application. Model is also a class which has all the objects and its properties and methods defined in it.

        - **View** : Layer has all the html controls which define the UI of the application. Here in MVC, we don’t have drag and drop option for controls as we don’t use server controls. Instead we use Razor Engine available with Visual Studio by default which helps in rendering the View.
        Views are files with .cshtml extensions. .cshtml contain both html and server code.
        And also, using `@`, we can access C# code so that in our page which can access server side dynamic data.

        - **Controller** : basically handles the request from user. It is the heart of the MVC application as everyone say. It is responsible to handle the request and return a response to user by loading appropriate View with data from Model.
        Controllers is nothing but a class with a group of methods called actions. And Every action method returns view. A View can be anything like it can be xml or html or JSON etc.

        - Generally, Data Access Layer is again a separate layer along with MVC Layers, like as we have in asp.net web application. DAL can contact Database and return result to Model.

        - Another important point to remember is, MVC is not totally new framework. It is built on top of asp.net, so all the features available in asp.net can be used in MVC as well. So it is called as Asp.net MVC.

        - Using MVC, once the application is developed, we can use the same logic for either asp.net MVC Application or phone app just by changing the View Layer of the application. So MVC also enhances reusability.

        - We can say MVC follows Front Controller approach because here it is that Controller which handles all requests whereas ASP.net Web Application follows Page Controller approach. i.e It is Page level at which incoming request is handled and act accordingly.

- ### Tag Helpers :

    - are a feature in ASP.NET Core MVC (and other related technologies) that allow you to create and render HTML elements more easily and with better integration into your server-side code. They are similar to HTML helpers but provide more flexibility and are more closely aligned with HTML syntax.


- ### Bootstrap : 

    - Bootstrap is a popular front-end framework for building responsive and mobile-first websites and web applications. It provides a set of pre-designed CSS and JavaScript components that make it easier to create consistent and visually appealing user interfaces