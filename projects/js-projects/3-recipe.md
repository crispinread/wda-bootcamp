# Recipe
Create an object to hold information on your favourite recipe. It should have properties for:

1. `recipeTitle` (a string)
1. `servings` (a number)
1. `ingredients` (an array of strings)
1. `directions` (a string)


Try displaying some information about your recipe.

*Bonus:* Create a loop to list all the ingredients.

## Function
Add a function called `letsCook` that says "I'm hungry! Let's cook..." with the name of your recipe title.

Call your new method.


## Resources and info

### Arrays of Objects
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

### Objects
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
