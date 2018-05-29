[Week 1 Home](../)

# Track, stage, and commit push! 

## Learning Competencies

- Define "commit"
- Demonstrate best practices for commit messages
- Describe the three states of a file in git (working, staged, commit)
- Stage and commit a file
- Push your file up to GitHub

## Summary

Git works by following all of the changes in the files inside a git tracked folder. The save point in git is called a commit. Think of a commit like a checkpoint in a video game. It is a point where you can go back to and look at the state of the files at that commit. Just like in a video game if make the wrong decision, you can go back to the checkpoint. A commit is your safety net if you accidentally introduce bugs in your code. You can revert to a working state while you debug your code. It is a great idea to commit often to create more frequent save points to fall back on.

## Exploration and Application

Exploration | Time to box |
------------|----------|
Refresh taster  | 10 minutes
Practice on your local repo | 30 minutes
Dig deeper | 20 minutes
Push | 5 minutes 
Practice again | 15 minutes
Reflect | 10 minutes

Be mindful of your time. Don't go deeper than you need to go.


## Refresh taster
Remember the GitHub [interactive tutorial](https://try.github.io/levels/1/challenges/1)? - its a simple way of practicing concepts like `git add` and `git commit` without getting bogged down by extra commands like `git checkout` (which we'll cover next). Cheatsheets (for terminal and git) are readily available online and also useful.

## Practice on your local repo
In the last deep dive challenge, you forked our repo and then cloned it onto your machine. You then created a new file called my_reflction.md

That file needs staging. You'll need to use commands like `git add` and `git commit`. 

__Good Commit Messages__

Because commits are 'save points', it is important to write good commit messages so you (and others) know what each commit includes.

Best practice. [GitHub recommends using past tense](https://stackoverflow.com/questions/3580013/should-i-use-past-or-present-tense-in-git-commit-messages?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa) (imperative) for your commits.

E.g "Make dog bark" (imperative) vs "Makes dog bark" or "Made the dog bark"

> Describe your changes in imperative mood, e.g. "make xyzzy do frotz" instead of "[This patch] makes xyzzy do frotz" or "[I]
> changed xyzzy to do frotz", as if you are giving orders to the codebase to change its behavior.
_github_

__Task__ Stage and commit your my_reflection.md file. Hint: Be sure to be in an appropraiate directory!

## Dig a little deeper
Identify what questions you have about GitHub. Craft your question and do some exploration.
And if you're still hungy, check out [Atlassins tutorial](https://www.atlassian.com/git/tutorials/saving-changes). Its fairly comprehensive so be sure to keep your focus within the scope of the learning competencies. .

Do you know how to check your commit history? Would you know where to look in each message to find what files were changed?
What do the terms working and staged mean?

Whenever you change the state of a file, it is tracked. You can check the status of all the files in the local repo by typing `git status` . If you have modified any files you will see some categories: Changes not staged for commit:, Changes to be committed:, and if you have created a new file, Untracked files:. No changes would return the message:

`On branch master
nothing to commit, working directory clean`


## Push 
Pushing your changes back up to GitHub. Right now your my_relection.md file lives on your computer, but its staged and ready to go. When you push your changes up, you'll be pushing to __the master copy of your forked version__. Don't worry, you won't be changing anything on our master copy. You have your own master copy and we have our ours. 

Git also gives you handy instructions below these categories. In untracked files it tells you how to add the files (use "git add <file>..." to include in what will be committed) from untracked to staged(changes to be committed), and how to remove a file from the added section to bring it back to untracked (use "git reset HEAD <file>..." to unstage).

## Practice again
Remember the reflections you've been collecting? Add them now to their own my_reflection.md files. Navigate around a bit. Can you see any my_reflection.md files already present? Make changes, check their status, stag them, commit and push them up to the cloud. 

