# JavaScript
REvise from here(soon will complete it)

JavaScript is used by 95% of all the websites which you can check [here](https://w3techs.com/technologies/details/cp-javascript).

JavaScript contains a standard library of objects, like Array, Date, and Math, and a core set of language elements like operators, control structures, and statements. 

Can be added to your HTML file in two ways:

**Internal JavaScript:** Add JavaScript code to HTML file by writing the code inside the <script> tag. Place <script> tag inside the <head> or the <body> tag according to the requirement.

**External JavaScript File:** Create a file with .js extension and paste the JavaScript code inside it. After creating the file -> add this file in <script src=”file_name.js”> tag inside <head> tag of the HTML file.

***HTML provide primary structure of a website whereas js makes websites interative and dynamic.***

## Why JavaScript is used?

-💎 Web pages with interactive elements: User interaction with web pages is enabled through JavaScript. On a web page, JavaScript has essentially no bounds.

-💎 Developing online and mobile applications: For web and mobile app development, developers can employ a variety of JavaScript frameworks.

-💎 Creating web servers and server applications: Aside from websites and apps, developers may use JavaScript to create simple web servers and Node.js to construct         backend infrastructure.

-💎 Game Development: Browser games can also be made using JavaScript. Beginning developers can use these to hone their JavaScript skills.

## What can we build using JavaScript ?
![buildjs](https://user-images.githubusercontent.com/90051406/198816790-a0278422-c01b-4471-9163-e50b8e06299a.png)

## Introduction to Object Oriented Programming in JavaScript

Some of the common interview questions in JavaScript on OOPS-

▪ How is Object-Oriented Programming implemented in JavaScript? 

▪ How does it differ from other languages? 

▪ Can you implement Inheritance in JavaScript?

▪ How to Become a JavaScript Developer? [click](https://www.geeksforgeeks.org/how-to-become-a-javascript-developer/) & so on…

![oopjs](https://user-images.githubusercontent.com/90051406/198821284-68693862-ac3c-45f3-bf94-fdf2ff53951b.png)


Note: A Method in javascript is a property of an object whose value is a function. 

Object can be created in two ways in JavaScript: `Using an Object Literal` & `Using an Object Constructor`

Classes: JavaScript is a prototype based Object Oriented Language, which means it doesn’t have classes, rather it defines behaviors using a constructor function and then reuse it using the prototype. 

Note: Even the classes provided by ECMA2015 are objects.

`JavaScript classes, introduced in ECMAScript 2015, are primarily syntactical sugar over JavaScript’s existing prototype-based inheritance. The class syntax is not introducing a new object-oriented inheritance model to JavaScript. JavaScript classes provide a much simpler and clearer syntax to create objects and deal with inheritance.
–Mozilla Developer Network`

Encapsulation:create a person Object using the constructor and Initialize its properties and use its functions. We are not bothered with the implementation details. We are working with an Object’s interface without considering the implementation details. 
Sometimes encapsulation refers to the hiding of data or data Abstraction which means representing essential features hiding the background detail. Most of the OOP languages provide access modifiers to restrict the scope of a variable, but their are no such access modifiers in JavaScript but there are certain ways by which we can restrict the scope of variables within the Class/Object.

Inheritance:
Note: The Person and Student object both have same method (i.e toString()), this is called Method Overriding. Method Overriding allows a method in a child class to have the same name and method signature as that of a parent class. 
In the above code, the super keyword is used to refer to the immediate parent class’s instance variable. 

## 7 JavaScript Concepts That Every Web Developer Should Know
[Convert this short form](https://www.geeksforgeeks.org/7-javascript-concepts-that-every-developer-must-know/)

## Advanced JavaScript Backend Basics

## Functional Programming in JavaScript

# JavaScript Array

-It is used to store multiple elements in a single variable.
![jsarray](https://user-images.githubusercontent.com/90051406/198825954-6c5413cb-c3d1-4ea6-ba0f-ddf042433753.png)

The Array.entries() method works on iterable objects such as an array (or any data iterable data structure) and it used to fetch all the entries of the same data structure. This method is used to get a new Array that contains the key and value pairs for each index of an array. 
