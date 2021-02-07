[Return to the Table of Contents](README.md)

# Reading Domain Modeling
  ## Summary
   - Domain modeling is the process of creating a conceptual model in code for specific program.
   - And a domain model that's articulated well can verify and validate your understanding of that problem.
   - Here's some tips to follow when building your own domain models
    1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
    2. Model its attributes with a constructor function that defines and initalizes properties.
    3. Model its behaviors with small methods that focus on doing one job well.
    4. Create instances using the `new` keyword followed by a call to a constructor function.
    5. Store the newly created object in a variable so you can access its properties and methods from outside.
    6. Use the `this` variable within methods so you can access the object's properties and methods from inside.


# Duckett HTML Book
  ## Chapter 6 Tables (pp. 126-145)
   ### What's a Table?
    - A table represents information in a grid format.
    - Examples of tables include financial reporrts, TV schedules, and sports results.
   
   ### Basic Table Structure
   - | `<table>` | The `<table>` element is used to create a table. The contents of the table are written out row by row. |
   - | `<tr>` |
    - You indicate the start of each row using the opening `<tr>` tag. (The tr stands for table row.)
    - It is followed by one or more `<td>` elements (one for each cell in that row).

   

# Duckett JS Book
  ## Chapter 3 Function, Methods, and Objects (pp. 106-144)
   ### Creating an Object: Constructor Notation
   - The new keyword and the object constructor create a blank object.
   - You can then add properties and methods to the object.
   ### Updating an Object
   - To update the value of properties, use dot notation or square brackets.
   - They work on objects created using literal or constructor notation.
   - To delete a property, use the `delete` keyword.
   ### Creating Many Objects: Constructor Notation
   - Sometimes you will want several objects to represent similar things.
   - Object constructors can use a function as a `template` for creating objects.
   - First, create the template with the object's properties and methods.
   - You create `instances` of the object using the constructor function.
   - The `new` keyword followed by a call to the function creates a new object.
   - The properties of each object are given as arguments to the function.
   ### Creating Objects Using Constructor Syntax
   ### Create & Access Objects Constructor Notation
   ### Adding and Removing Properties
   ### Recap: Ways to Create Objects
   ### This (It is a Keyword)
   - The keyword `this` is commonly used inside functions and objects.
   - Where the function is declared alters what `this` means.
   - It always refers to one object, usually the object in which the function operates.
   ### Recap: Storing Data
   - In JavaScript, data is represented using name/value pairs.
   - To organize your data, you can use an array or object to group a set of related values.
   - In arrays and objects the name is also known as a key.
   - If you want to access items via a property name or key, use an object (but note that each key in the object must be unique).
   - If the order of the items is important, use an array.
   ### Arrays are Objects
   - Arrays are actually a special type of object.
   - They hold a related set of key/value pairs (like all objects), but the key for each value is its index number.
   ### Arrays of Objects and Objects in Arrays
   - You can combine arrays and objects to create complex data structures:
    1. Arrays can store a series of objects (and remember their order).
    2.