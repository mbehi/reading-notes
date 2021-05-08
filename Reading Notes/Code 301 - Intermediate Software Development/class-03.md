[Return to the Table of Contents](README.md)

# Passing Functions as Props

## Reading

### [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

1. What does .map() return?

   1. .map() returns an array of numbers and doubles their values
2. If I want to loop through an array and display each value in JSX, how do I do that in React?

   1. ```
      const numbers = [1, 2, 3, 4, 5];
      const listItems = numbers.map((number) =>
      <li>{number}</li>
      );
      ```
3. Each list item needs a unique indentifier.
4. What is the purpose of a key?

   1. A 'key' is a speical string attribute you need to include when creating lists of elements.

### The Spread Operator

1. What is the spread operator?

   1. In Javascript, spread syntax refers to the use of an ellipsis of three dots (...) to expand an interable object into the list of arguments.
2. List 4 things that the spread operator can do.

   1. Copying an array
   2. Concatenating or combining arrays
   3. Adding an item to a list
   4. Adding to state in React
3. Give an example of using the spread operator to combine two arrays.

   1. ```
      const myArray = [`🤪`,`🐻`,`🎌`]
      const yourArray = [`🙂`,`🤗`,`🤩`]
      const ourArray = [...myArray,...yourArray]
      console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
      ```
4. Give an example of using the spread operator to add a new item to an array.

   1. ```
      const fruits = ['🍏','🍊','🍌','🍉','🍍']
      const moreFruits = [...fruits];
      console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
      fruits[0] = '🍑'
      console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍
      ```
5. Give an example of using the spread operator to combine two objects into one.

   1. ```
      [...["😋😛😜🤪😝"]] // Array [ "😋😛😜🤪😝" ]
      [..."🙂🙃😉😊😇🥰😍🤩!"] // Array(9) [ "🙂", "🙃", "😉", "😊", "😇", "🥰", "😍", "🤩", "!" ]

      const hello = {hello: "😋😛😜🤪😝"}
      const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}

      const helloWorld = {...hello,...world}
      console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" }
      ```

## Video

### [How to Pass Functions Between Component](https://www.youtube.com/watch?v=c05OL7XbwXU)

1. In the video, what is the first step that the developer does to pass functions between components?
2. In your own words, what does the "increment" function do?
3. How can you pass a method from a parent component into a child component?
4. How does the child component invoke a method that was passed to it from a parent component?

## Bookmark / Skim

* [React Tutorial through 'Declaring a Winner'](https://reactjs.org/tutorial/tutorial.html)
* [React Docs - Lifting State Up](https://)
