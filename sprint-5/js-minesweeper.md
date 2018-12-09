[Sprint 5 Home](README.md)|
---|

# Minesweeper

Before you jump into coding minesweeper, if you're unfamiliar with how the game works it might be worth having a look at this resource [???](https://www.google.com/search?q=minesweeper) to help you get familiar with the game itself and the rules it has.

>This is what minesweeper is

>First part = follow the error messages you receive back when you load it in the browser
>Second part = complete the functions, use your problem solving skills to get it working

>Here is the file

>You will want to clone it and complete this locally, push back to your repo, turn on github pages for it so we can see it too!


>Have Fun! :+1:

## And so it begins!

In your sprints you have covered some of the skills necessary to build your first JavaScript game. This sprint, you'll actually build it - with help - step by step.

Create a fork of this repo: https://github.com/dev-academy-foundations/minesweeper

Clone your copy of the repository down using `git clone https://github.com/your-name/minesweeper` (replacing your-name with your GitHub account name.)

cd into the minesweeper directory

You'll see a stylesheet file, a JavaScript file, an HTML file, and some SVG images. There's also a `lib` directory.

You can ignore the images and CSS, although you can take a look at the styles if you're curious. You can also ignore the lib directory (this contains two JavaScript files which do a lot of the heavy lifting for you. We do not expect you to understand everything that's in them! In fact, you should be able to complete the whole challenge without even glancing inside them).

Open the `index.html` in your code editor. You don't need to actually modify it at all, but it helps to get an idea of what's inside.

Notice that we have a containing div with class board but... it's empty! We're going to fill that up with cells, but we're going to do it using our JavaScript skills.
 
Open the `index.html` in your internet browser. You should see a message near the top of the screen telling you to define a board object.

Right then, let's get something working! Open up minesweeper.js and take a look. Uncomment the var board = near the top and then complete the statement by adding {}, defining board as an empty object.

Save the file and reload the page in your browser. It should tell you to add a cells property.

Do that, reload the page in the browser and see what the next message is. Keep repeating this cycle until you actually see a game board appear!

- You can make the board as large as 36 cells before the game will complain it's too large. We suggest 9 cells (three on each side) to begin with.

- You should probably start all your mines as hidden: true!

Once you've got a board displaying, you can play parts of the game! Don't forget though:

Commit your changes to your local branch and push to GitHub.

## Objects and Arrays

Ok, so we have a game board! (If you're not doing these in order, you need to: make sure you complete 6.0 first, or this will make no sense at all!) Now we need to show how many mines are in surrounding squares as we reveal more of the board.

If you've never played Minesweeper, maybe you should play a couple of games to get the hang of it at this point. Timebox it though: don't get addicted! There's a pretty solid version here.

In 6.0 we created a board object. If we were describing our object in English, we'd say something like: "This is an object that contains an array of objects."

```
var board = {
  cells: [
    {
      row: 0,
      col: 0
      // ...
    },
    {
      row: 0,
      col: 1
      // ...
    }
  ]
}
```

Tip: if you're not sure if the board object you're creating is correct, open your browser's developer tools and type board. In Chrome at least, this will show the object's structure and you can expand the cells array to see its contents.

In bootcamp you're going to need to access objects and arrays like this all the time! Getting familiar with them is crucial. Be sure that you understand the following before going onto the next assignment:

- cells is an object property.

- You can access (get) a property on an object by using either dot notation (board.cells) or bracket notation (board['cells']).

- The value inside the brackets in bracket notation can be a string variable: (board[propertyName]).

- You can access the first object inside the cells array using dot and array notation (board.cells[0]) or bracket and array notation (board['cells'][0]).

- You can access a property on that object using dot and array notation (board.cells[0].row).

If you're not clear on any of these things, this is a really good time to reach out and seek clarification! Ask your fellow Phase-0 students in Slack, ask in #code-help-desk, ask a teacher. Most importantly, practise. Sometimes the best way is just to try it, either in the browser development tools or using an online tool like Repl.it.

## Counting the Boom

So far, we've created a global object, a data structure that we can use to track information about our game. It's worth noting that, as a rule, relying on objects in global scope isn't always such a great idea. However it makes things a bit less complicated while you're learning the ropes! Once you've gotten the hang of working with objects and properties, you'll realise that we very seldom need to keep them in global scope.

Now we need to find a way to display those counts of how many of the surrounding cells contain mines, the counts that make Minesweeper more than just a random guessing game. There's some slightly trickier code here, so we've provided some of it for you in lib.

Now, we're using our global board object to store information about the game board. One of the pieces of information we can store is how many mines surround each cell. We don't have to store where those mines are in relation to the cell, but we do have to count them. This will be used to display the hints that Minesweeper players get when they clear a cell, telling them where the next safe cell might be. Cell objects will end up looking something like this:

```
{
  row: 0,
  col: 1,
  isMine: false,
  isMarked: false,
  hidden: true,
  surroundingMines: 2
}
```

In startGame, above lib.initBoard(), write a for loop. This should loop through the contents of board.cells. (Remember, board.cells is an array of objects.)

The loop's only job should be to call countSurroundingMines once for each cell in board.cells. You'll need to pass each cell as an argument (the bit in the parentheses).

Assign the result of countSurroundingMines to a property on each cell object. The new property should be called surroundingMines.

Further down in the file you'll see the function countSurroundingMines. Your job is to define it so it returns the number of cells around the current cell that have the isMine property set to true.

Getting the cells that surround the current cell is pretty tricky, so we've provided a helper function: lib.getSurroundingCells. Read the comments above countSurroundingMines for more clues.

To be clear, you don't need to write lib.getSurroundingCells... you can just start using it!
You'll need to use a syntax that looks something like: var surroundingCells = getSurroundingCells(row, col);

Think about how to get row and col out of your cell object: remember dot and bracket notation?

You're going to have to loop through the surrounding cells returned from getSurroundingCells, checking each one to see if it's a mine and adding to a count variable if it is.

Once you have the correct count, return it (return count).

Once you've got the counts working to your satisfaction, commit your code!

## Win some, lose some

So now we can play a game... almost! You've probably noticed that there's no real way to declare a winner. You can just continue merrily uncovering cells to your heart's content. We can change that now by creating a win condition: a way to tell our game that it's over.

You should go into this knowing that the way to win a game of Minesweeper is to have correctly marked all of the mines and uncovered every other cell.

Remember event handlers? You defined some of them in Sprint 5. In startGame, use document.addEventListener to call checkForWin every time the left mouse button is clicked.

When you've done that, add another one that calls checkForWin when the right mouse button is clicked.

Remember, a player can win either by clearing the last hidden cell, or marking the last mine.

Define the checkForWin function. It should loop through all of board.cells.

For each cell, check to see if both .isMine and .isMarked are true. If any mine still exists that isn't marked, the player hasn't won yet and you can return out of the function.

If every mine is marked, but there are still cells with the hidden property set to true, the player hasn't won yet and you can return out of the function.

If both these criteria pass, the player has won! There's a displayMessage function call at the bottom of checkForWin you can use to tell them so.

Take a moment to notice something: we're defining small functions that only have one job, rather than big complex chunks of code. This is an important principle of software development which we will be spending more time on later: where possible, try to have your functions do one thing, and name them appropriately.

When you're done, commit your code!

Hey, it's a game! The next assignment contains some finishing off tasks and stretch goals.

Please do the push to GitHub Pages regardless though, and share your work with the your fellow Phase-0 students.

## Finishing Touches

Congratulations on making it this far! We hope you enjoyed (or at least were not driven to distraction by) this little journey through a classic game.

The basics are complete, but there are so many more things to work on. Here are some stretch goals if you're done ahead of time and your other assignments for this sprint are complete. Don't get too bogged down in trying to make your game perfect: it's much more important that you learn the principles behind it.



#### Stretch Goal 1: automatically generate the board! 
Instead of just typing out the global board object, write a function to create it.
Each cell will need row, col, isMine, isMarked, and hidden properties.
You could start by simply setting every isMine to true, but later you'll probably want to have a random number of mines scattered throughout the board.
#### Stretch Goal 2: reset the board!
After a win or loss, give players a chance to try again by resetting the board to its default state. You'll need to put classes back the way they were at the start, and re-initialise the global board object.
#### Stretch Goal 3: sound effects!
Investigate how to use JavaScript to play a sound when the user uncovers or marks a cell. Play an explosion when they uncover a bomb, and applause when they win.
Resource: Play sound on :hover
#### Stretch Goal 4: you decide!
Let your imagination run rampant. Maybe they're not mines after all, but kumquats! Restyle the board, change the rules, make it your own.

## When you've finished
- upload the game to GitHub Pages so other people can play it.
- Select 'Project site', then 'Start from scratch', and follow the instructions.
- When you've published your game, add a link to it in the waffle comments below.
- Post the link to the #show-eda channel on Slack with the hashtag #minesweeper!

-reate a pull request back