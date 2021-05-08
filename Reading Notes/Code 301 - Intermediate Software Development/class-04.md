[Return to the Table of Contents](README.md)

# React and Forms

## Reading

### [React Docs - Forms](https://reactjs.org/docs/forms.html)

1. What is a 'Controlled Component'?
   1. In HTML, form elements such as <input>input, textarea, and select typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().
2. Should we wait to store the users responses from the form into state when they submit the form OR shoudld we update the state with their responses as soon as they enter them? Why.
   1. Update the State with their responses as soon as they enter them. Because it is the most efficient way.
3. How do we target what the user is entering if we have an event handler on an input field?
   1. Event.Target.Name

### [## The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff?gi=f2bfd974b831)

1. Why would we use a ternary operator?
   1. It allows you to use shorter code for an if else statement.
2. Rewrite the following statement using a ternary statement:
   ```
   condition ? value if true : value if false

     if(x===y){
    console.log(true);
     } else {
    console.log(false);
     }
   ```

## Bookmark / Skim

* [React Bootstrap - Forms](https://react-bootstrap.github.io/components/forms/)
* [React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)
