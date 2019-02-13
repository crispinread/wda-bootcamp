---
layout: page
title: JavaScript Projects 2
subtitle: JavaScript Projects for our Pre Apprenticeship Training
use-site-title: true
permalink: /projects/js2
---
## Even/Odd Counter
Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even")

## The Reading List
Keep track of which books you read and which books you want to read!

1. Create an array of objects, where each object describes a book and has properties for the title (a string), author (a string), and alreadyRead (a boolean indicating if you read it yet).
1. Iterate through the array of books. For each book, log the book title and book author like so: "The Hobbit by J.R.R. Tolkien".
1. Now use an if/else statement to change the output depending on whether you read it yet or not. If you read it, log a string like 'You already read "The Hobbit" by J.R.R. Tolkien', and if not, log a string like 'You still need to read "The Lord of the Rings" by J.R.R. Tolkien.'

## Recipe
Create an object to hold information on your favourite recipe. It should have properties for:

1. `recipeTitle` (a string)
1. `servings` (a number)
1. `ingredients` (an array of strings)
1. `directions` (a string)


Try displaying some information about your recipe.

*Bonus:* Create a loop to list all the ingredients.

### Function
Add a function called `letsCook` that says "I'm hungry! Let's cook..." with the name of your recipe title.

Call your new method.


### Resources and info

#### Arrays of Objects
Because arrays can hold any data type, they can also hold objects.
```javascript
var users = [
  {name: 'Jolene', age: 21},
  {name: 'Alexa',  age: 18}
];

for (var i = 0; i < users.length; i++) {
  var user = users[i];
  console.log(user.name + ' is ' + user.age + ' years old.');
}
```

#### Objects
Just like other data types, objects can be passed into functions:
```JavaScript
var jolene = {
  age: 21,
  hairColor: 'Auburn',
  likes: ['pizza', 'tacos'],
  birthday: {month: 3, day: 14, year: 1995}
}

function describeUser(user) {
  console.log('You are ' + user.age + ' years old with '
  + user.hairColor + ' hair.');
}

describeUser(jolene);
```

### Object methods
Objects can also hold functions.

```JavaScript
var jolene = {
  age: 21,
  hairColor: 'Auburn',
  talk: function() {
    console.log('Hello!');
  },
  eat: function(food) {
    console.log('Yum, I love ' + food);
  }
};
```
Call object methods using dot notation:
```JavaScript
jolene.talk();

jolene.eat('pizza');
```
## Times Tables
Write a program to output the times tables from 1 through to 12. Use a loop within a loop.

### For Loop
[`for`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for) loops - declare a counter in the statement
```javascript
// will count 1 to 10
for (var i = 1; i <= 10; i++) {
  console.log(i);
}
```

### Loops and Logic

```javascript
// Count from 1 to 100

for (var i = 1; i <= 100; i++) {
  if (i % 3 === 0) {
    // Says 'Fizz' after multiples of three
    console.log(' Fizz');
  } else if (i % 5 === 0) {
    // Says 'Buzz' after multiples of five
    console.log(' Buzz');
  } else {
    console.log(i);
  }
}
```

### Break
To exit a loop, use the [`break`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/break) statement.
```JavaScript
// Count from 100 to 200
for (var i = 100; i <= 200; i++) {
  console.log('Testing ' + i);

  //Stop at the first multiple of 7
  if (i % 7 == 0) {
    console.log('Found it! ' + i);
    break;
  }
}
```
## Top Choice
Create an array to hold your top choices (colors, presidents, whatever). For each choice, log to the screen a string like: "My #1 choice is blue."

**Bonus:** Change it to log "My 1st choice, "My 2nd choice", "My 3rd choice", picking the right suffix for the number based on what it is. [The method slice](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/slice) might be helpful here.
