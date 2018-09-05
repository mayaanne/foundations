[Sprint Index](../README.md) | [Resources Index](README.md) |
------------|----------|

# Pseudocode 
Pseudocode is a kind of structured english for describing code and algorhythms. It uses the structural conventions of a normal programming language, but is intended for human reading rather than machine reading. It allows the designer to focus on the logic of the algorithm without being distracted by details of language syntax. The pseudocode needs to be complete, from start to finish and describes the entire logic, line by line. 

Example 1:  
If you are trying to convert every letter in a string to a number based on its location in the alphabet, you would probably want more info than this:

```
// PSEUDOCODE
// Input = string with letters
// Output = string with numbers

// Convert all letters into their numbers
```
Instead, you would probably want something more like:

```
// PSEUDOCODE
// Create array all letters
// Split input of letters into array
// Iterate through the input array 
// Check index of letter in all_letters array
// index = index + 1
// push index to new array
// Convert finished array of numbers to string
```

Example 2:
Create a game where you collect treasure to move up to the next level. Make sure to avoid the dragon. 

```
// PSEUDOCODE
// Declare a 'player' object that will have properties as position and success
// Add different methods to 'player' to make it move up, down, forward and backward
// Declare a 'dragon' object and give it a random position
// Move the player, and also assign another random position to Dragon
// Check where player is with respect to the dragon and gold
// If its the same position as gold, success! If the player position is same as dragon,
// game over!
```

Pseudocode is for you. It may seem trivial and silly for simple challenges, but its an important and necessary step when you are working on more complex problems. You will want to get into practice of pseudocoding early so you are prepared for organizing your thoughts when it's required.


### Hallmarks of Good Pseudocode

__English-like statements are used to precisely describe specific steps in the process__  
Full sentences aren't necessary, but variable names are fine to use and should make sense.

__Contains clearly defined inputs and outputs__ 
Defining the given conditions and the ultimate result explicitly allows the steps of the process to be contextualized and more easily understood.

__Code-specific syntax is avoided and a more a abstract, higher level is adhered to__
The nuances of JavaScript should be avoided, but common programming shorthands are OK. If-then-else statements or loops are well known shorthands, as well as defining and passing parameters.

__Formatting that clearly displays larger steps and respective smaller steps__
A traditional outline is a good example of helpful formatting. It's best to use some convention to group statements(indention, begin/end, curly braces, etc), but don't obsess over small details like proper punctuation.

```
Set moveCount to 1
FOR each row on the board 
    FOR each column on the board 
        IF gameBoard position (row, column) is occupied THEN 
            CALL findAdjacentTiles with row, column
            INCREMENT moveCount 
        END IF 
    END FOR
END FOR
```

__Appropriate granularity and ease of conversion to code__  
The attention to detail should ensure that problematic nuances of the code are addressed at the high level, and systemic problems can be tackled appropriately. This should be balanced with readability.

__Intention is emphasized over implementation__ 
Making the intent of the problem approach clear should be emphasized over the specifics of implementation in a target language. Try to keep the context of the problem in mind, with the goal and output clearly defined.  



## Inital Solution   

Now you actually get to code! Your entire goal here is to translate your pseudocode into code. This should be easy if you took your time to pseudocode well.

If your pseudocode is not easy to implement, modify it and re-attempt to code it. 

Run your code often to check whether you are successfully passing your driver code or tests.

When you've passed each test, give yourself a pat on the back! Then take a break before trying to refactor. It's good to give your eyes a rest so they can more easily see places to improve.

__NOTE:__
If you can't get your code to pass after spending too much time for comfort on it, take a break or move on. Simply write in the comments that you couldn't get it fully working. Try to identify where the problem was, and ask for help from your cohort.

We do not recommend working 8 hours straight on one challenge (or even 3 hours). The point of these challenges is to challenge yourself and recognize when you need help or have hit a wall.


### Debugging
Some tips for finding where your code isn't working

- Include `console.log` statements to find out what your code is doing 


