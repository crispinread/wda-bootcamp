Write a program to output the times tables from 1 through to 12. Use a loop within a loop.

## For Loop
[`for`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for) loops - declare a counter in the statement 
```javascript
// will count 1 to 10
for (var i = 1; i <= 10; i++) {
  console.log(i);
}
```

## Loops and Logic

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

## Break
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
