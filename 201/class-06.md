[Return to the Table of Contents](README.md)

# Duckett JS Book
   ## Understanding the Problem Domain is the Hardest Part of Programming
   - If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:
      1. Make the problem domain easier.
      2. Get better at understanding the problem domain.
   - You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.
   - TIP: It is easy to fall into the trap of thinking you understand enough of the problem to get started coding it.

   ## Chapter 3 Object Literals
    What is an Object?
     - Objects group together a set of variables and functions to create a model of a something you would recognize from the real world.
     - In an object, variables and functions take on new names.

    Creating an Object: Literal Notation
     - Literal notation is the easiest and most popular way to create objects.
     - There are several ways to create objects.   

    Accessing an Object and Dot Notation
     - You access the properties or methods of an object using dot notation.
     - You can also access properties using square brackets.
   
    Creating Objects: Constructor Notation
     - The new keyword and the object constructor create a blank object.
     - You can then add properties and methods to the object.

    Updating an Object
     - To update the value of properties, use dot notation or square brackets.
     - They work on objects created literal or constructor notation.
     - To delete a property, use the delete keyword.

    This (It is a Keyword)
     - The keyword this is commonly used inside functions and objects.
     - Where the function is declated alters what this means.
     - It always refers to one object, usually the object in which the function operates.

    Recap: Storing Data
     - In JavaScript, data is represented using name/value pairs.
     - To organize your data, you can use an array or object to group a set of related values.
     - In arrays and objects the name is also known as a key.

    Arrays are Objects
     - Arrays are actually a special type of object.
     - They hold a related set of key/value pairs (like all objects), but the key for each value is its index number.
   
    Arrays of Objects and Objects in Arrays
     - You can combine arrays and objects to creat complex data structures: Arrays can store a series of objects (and remember their order).
     - Objects can also hold arrays (as values of their properties).

    What are Built-In Objects?
     - Browsers come with a set of built-in objects that represent things like the browser window and the current web page shown in that window.
     - These built-in objects act like a toolkit for creating interactive web pages.

    Global Objects: String Object
     - Whenever you have a value that is a string, you can use the properties and methods of the String object on that value.
     - This example stores the phrase "Home sweet home" in a variable.

    Data Types Revisited
     - In JavaScript, there are six data types: 
      1. Five of them are described as simple (or primitive) data types.
      2. The sixth is the object (and is referred to as a complex data type).

   ## Chapter 5 Document Object Model 
    Summary
     - The browser represents the page using a DOM tree.
     - DOM trees have four types of nodes:
      1. Document Nodes
      2. Element Nodes
      3. Attribute Nodes
      4. Text Nodes
    - You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax. 
    - Whenever a DOM query can return more than one node, it will always return a NodeList.
    - From an element node, you can access and update its content using properties such as textContent and innerHTML or using DOM manipulation techniques.
    - An element node can contain multiple text nodes and child elements that are siblings of each other.
    - In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).
    - Browsers offer tools for viewing the DOM tree.