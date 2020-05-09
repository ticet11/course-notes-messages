# Essay Questions

## MongoDB for Developers

**What is MongoDB**

- A document based database.

**What is a MongoDB Collection**

- Basically, a table of your documents.

**What is a Document and how do you use them in MongoDB?**

- A document contains a piece of data in your database.

**What is the find() method used for?**

- Retrieving documents.

**What is the .pretty used for?**

- Organizes the information in an easier to read format.

**What is the difference between SQL databases and MongoDB**

- SQL is a relational database, MongoDB is not. SQL is a bit more restrictive, but that can make it a safer choice, especially with more complex systems.

**How would you add a document in a MongoDB database**

        $ db.collection.insert({
             key: 'value'
         })

**How would you use a projection?**

- Projection specifies which properties of a document to return when it is queried.

**How do you run a local instance of mongo**

        $ mongo

**How would you delete a document**

        $ db.collection.remove({ identifying info })

## Introduction to JavaScript

**How do you set variables in javascript**

- Declare the type of variable (var, const, let), then display the name, followed by a single = to assign the variable whatever follows.

- eg. const hotdog = 'Ballpark';

**What is javascript hoisting**

- In JavaScript, you can declare a variable anywhere on the page (within the correct scope) and the code will still treat it as if it was declared at the top.

**List 3 javascript datatypes**

- array
- number
- object

**What is the order of operations in Javascript**

- PEMDAS

**How do you use conditionals in javascript?**

    if (requirements) {
        action;
    }

**What is a switch statement, and how would you use one?**

- It's similar to an if else statement, but gives several cases to loop through.

        switch(expression) {
        case x:
            // code block
            break;
        case y:
            // code block
            break;
        default:
            // code block
}

**What is a ternary operator**

- An if else statement that gives a single expression and returns one option if it's true and another if it's not.

        a > b ? console.log('a is greater than b') : console.log('b is greater than a')

**What is a function?**

- a function is a block of code that can be reused or called in a different part of the program.

**What is a function argument?**

A function argument is a variable that a function requires to be run.

**What is the "this" keyword in javascript?**

- 'this' is a keyword used in a class that references the specific instance of the class being worked with. Can be used in other parts of JavaScript, like in an arrow function and the different context changes the way that it can be used.

**What is a Javascript array?**

- A list. ['like', 'this']

**What is a Javascript object?**

- A dictionary, basically. Key and value pairs. { like: 'this' }

**List 3 types of javascript loops**

- for, while, forin

## Modern JavaScript

**Explain the const variable.**

- const can not be reassigned or re-initialized

**What do you use for modern string interpolation in Javascript**

        variable = 'use';
        return `This would be a good ${variable}.`;

**Explain an arrow function and how you might use one**

- A concise way to use anonymous functions.

        button.mousePressed((x, y) => x + y);

**What is array destructuring?**

- It's a way to access nested information in a more efficient way, as well as setting variables with that information.

**What is the javascript spread operator what is it used for?**

- Will let you access individual items in an array.

**How does the this keyword work with arrow functions**

- The 'this' keyword scope changes in an arrow function. The arrow function does not create it's own 'this'. 'this', instead accesses the 'this' of the enclosing body.

**How do you pass a javascript object as function arguments by leveraging deconstruction?**

        someFunc({foo: "This is", bar: "a thing!"});

**What is a Javascript Promise?**

- A promise creates asyncronous values. Basically, a variable is not yet set, but will be used when it is.

**What is a Javascript fetch Promise and how might you use it?**

- It is the response that you receive from a fetch request. You can really choose how to use it. You can convert the data or display the data, etc.

**What is async and await in javascript and what purpose does it serve in Javascript?**

- A new way to write an asyncronous function. You can write out your function in a way that makes the steps wait for the previous step to resolve before executing.(syntactic sugar)

**What is error handling in a Javascript async/await function, and how might you use it?**

- Error handling is just how you handle a situation where you don't retrieve the data you're looking for.