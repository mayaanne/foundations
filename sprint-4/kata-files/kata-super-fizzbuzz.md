[Katas Home](../js-katas.md)

# FizzBuzz (Super Edition)

## Learning Competencies
- Use strings, integers, arrays, functions
- Use if/else or switch statements, string methods, for loops

## Summary:

FizzBuzz is a classic programming exercise (and fairly common interview question).

The usual example asks the developer to write a program which prints out each number from 1 to 100.  But for multiples of 3 print 'Fizz' instead of the number and for multiples of 5 print 'Buzz'.  For numbers which are multiples of both 3 and 5 print 'FizzBuzz'.

This exercise has a little twist.  Write a method called `super_fizzbuzz` which takes as its input an `Array` of integers.

It should return a "fizzbuzzed" `Array`, i.e., the array is identical to the input with the following substitutions:

1. Multiples of `3` should be replaced with the string `"Fizz"`
2. Multiples of `5` should be replaced with the string `"Buzz"`
3. Multiples of `15` should be replaced with the string `"FizzBuzz"`
```
For example:

super_fizzbuzz([1,2,3])     // will return [1, 2, "Fizz"]
super_fizzbuzz([1,2,5])     // will return [1, 2, "Buzz"]
super_fizzbuzz([1,2,15])    // will return [1, 2, "FizzBuzz"]

super_fizzbuzz([30, 9, 20, 1])      // will return ["FizzBuzz", "Fizz", "Buzz", 1]
```

---

## Write Pseudocode

To start, think through what needs to happen in your function and write pseudocode comments for the steps it will have.

## Write your initial solution

Write code to match your pseudocode steps. You may find you have to do things in a different order than you originally wrote in your pseudocode or add more steps in, and that's alright! The pseudocode is a first pass, you don't have to match it exactly.

Once written, run the tests. If your initial solution passes all tests, move on to the next steps.

>## Stretch: Refactor your code

>## Submit and Reflect