[Sprint 2 Home](../README.md)

# JavaScript Olympics


## Learning Competencies
- Create and manipulate objects in JavaScript
- Define functions in JavaScript
- Use JavaScript built-in methods
- Debug using Node's error messages

## Summary
It is finally time...for the Foundation JavaScript Olympics! You will be completing a pentathlon of challenges to stretch your JavaScript knowledge. You will be going through a variety of tasks, some of them you will know how to do already, some will test your research abilities.

## Release 0: Warm up: Objects

Create athlete profiles for you and a friend. Include your name, height, sport, and quote. You can use object literal notation for this exercise. Validate that your properties are properly defined by writing tests and running the code in Node.

## Release 1: Bulk up: Add properties to objects

Create a function that takes an array of athletes and adds a property `win` to each athlete in the array. `win` should print "{name} won the {event}!"

Would it make more sense to have `win` be defined as a function expression or a function declaration?

## Release 2: !sdrow ruoy elbmuJ: Reverse a string

Create a function that accepts a string as an argument and reverses it.

Use the built-in JavaScript methods for strings and arrays to accomplish this. See the MDN [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) and [Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter) docs.


## Release 3: 2, 4, 6 ,8! Who do we appreciate?: Remove odd numbers from an array

Create a function that accepts an array of numbers. Return an array with only the even numbers.

You can do this manually or use built-in JavaScript [Array Methods](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter).


## Release 4: "We Built this City": Build a constructor function

Test code has been provided for you. Copy and paste it to your [my_solution.js](my_solution.js) file. Read the definition of a constructor function from this excellent (albeit old) [article](http://code.tutsplus.com/tutorials/the-basics-of-object-oriented-javascript--net-7670). This is a great article to return to when you have the time to learn more about constructor functions.


```javascript
var michaelPhelps = new Athlete("Michael Phelps", 29, "swimming", "It's medicinal I swear!")
console.log(michaelPhelps.constructor === Athlete)
console.log(michaelPhelps.name + " " + michaelPhelps.sport + " " + michaelPhelps.quote)
```


## Release 5: Reflect

Whew! Nice work, you must be exhausted, take some time to cool down and reflect. Include your reflection in your [Sprint 3 reflections file](../../my-reflections-sprint-3.md) file. This should take about 10-15 minutes.
