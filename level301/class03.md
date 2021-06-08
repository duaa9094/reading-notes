# React Docs - lists and keys

1. What does .map() return?

An array contain the output of call back function

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

3. Each list item needs a unique **Key**.

4. What is the purpose of a key?
Keys help React identify which items have changed, are added, or are removed


# The Spread Operator

1. What is the spread operator?
>The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.


2. List 4 things that the spread operator can do.

Copying an array

Concatenating or combining arrays

Using Math functions

Using an array as arguments 


3. Give an example of using the spread operator to combine two arrays.

    const myArray = [`🤪`,`🐻`,`🎌`]

    const yourArray = [`🙂`,`🤗`,`🤩`]

    const ourArray = [...myArray,...yourArray]

    console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩


4. Give an example of using the spread operator to add a new item to an array.

    const fewFruit = ['🍏','🍊','🍌']

    const fewMoreFruit = ['🍉', '🍍', ...fewFruit]

    console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]


5. Give an example of using the spread operator to combine two objects into one.
    const objectOne = {hello: "🤪"}

    const objectTwo = {world: "🐻"}

    const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}

    console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }

    const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}

    objectFour.laugh() // 😂😂😂😂😂


# How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?
Creat  function to pass an object


2. In your own words, what does the increment function do?

Updates the value of the counts based on the name that passed 

3. How can you pass a method from a parent component into a child component?

The function is passed as a props to a child component

4. How does the child component invoke a method that was passed to it from a parent component?

onClick during data flow