# Manipulating JavaScript Objects

## Learning Competencies
- Define local variables in JavaScript
- Create, add properties to, delete properties from, and access values from JavaScript Object literals
- Use pre-written tests to drive development

## Summary

In this challenge you will work with the following JavaScript object that has been assigned to the variable `terah`. You will have to complete each task without modifying the object itself. That means everything must be done outside of the curly braces.

Hint: You'll find object constructor notation very useful for this exercise.

```javascript
var terah = {
  name: "Terah",
  age: 32,
  height: 66,
  weight: 130,
  hairColor: "brown",
  eyeColor: "brown"
}
```

## [repl.it](https://repl.it/@kelly_keating/Manipulating-JS-Objects)
> Follow link, fork to own account

## Run the tests 
Run the code on your forked repl.it challenge. All tests will log `true` in the console when they pass--`false`, otherwise.

## Pass the Tests
You'll want to follow the outline below. Note that each step should build on but not modify any of the code before it.

1. Define a variable adam and use object literal notation to assign this variable the value of an object with no properties

2. Give `adam` a name property with the value "Adam".

3. Add a spouse property to `terah` and assign it the value of `adam`.

4. Change the value of the `terah` weight property to 125.

5. Remove the eyeColor property from `terah`.

6. Add a spouse property to `adam` and assign it the value of `terah`.

7. Add a children property to `terah` and and use object literal notation to assign
 this variable to an empty object.

8. Add a `carson` property to the value of the `terah` children property. `carson` should be an object with a property `name` with the value "Carson".

9. Add a `carter` property to the value of the `terah` children property. `carter` should be an object with a property `name` with the value "Carter".

10. Add a `colton` property to the value of the `terah` children property. `colton` should be an object with a property `name` with the value "Colton".

11. Add a children property to `adam` and assign it the value of `terah.children`.

Follow the steps below to make the tests pass and complete the challenge.
The order of the steps corresponds to the order of the tests. After completing
each step, run your code to be certain that the next test has passed.

When all of the tests have passed, your final `terah` object will be logged to the console.

## Submit it 
> Put your link somewhere?
