[Week 1 Home](../)

# Tracking Changes

## Learning Competencies

- Define "commit"
- Demonstrate best practices for commit messages
- Describe the three states of a file in git (working, staged, commit)
- Stage and commit a file

## Summary

Git works by following all of the changes in the files inside a git tracked folder. The save point in git is called a commit. Think of a commit like a checkpoint in a video game. It is a point where you can go back to and look at the state of the files at that commit. Just like in a video game if make the wrong decision, you can go back to the checkpoint. A commit is your safety net if you accidentally introduce bugs in your code. You can revert to a working state while you debug your code. It is a great idea to commit often to create more frequent save points to fall back on.

## Exploration and Application

Exploration | Time to box |
------------|----------|
Refresh taster  | 10 minutes
Practice on your local repo | 30 minutes
Dig deeper | 20 minutes
Reflect | 10 minutes

Be mindful of your time. Don't go deeper than you need to go.


## Refresh taster
Remember the GitHub [interactive tutorial](https://try.github.io/levels/1/challenges/1)? - its a simple way of practicing concepts like `git add` and `git commit` without getting bogged down by extra commands like `git checkout` (which we'll cover next). Cheatsheets (for terminal and git) are readily available online and also useful.

## Practice on your local repo
In the last deep dive challenge, you forked our repo and then cloned it onto your machine. You then created a new file called my_reflction.md

That file needs staging. You'll need to use commands like `git add` and `git commit` and you'll need to make sure your in the correct directory.

__Good Commit Messages__

Because commits are 'save points', it is important to write good commit messages so you (and others) know what each commit includes.

Best practice. [GitHub recommends using past tense](https://stackoverflow.com/questions/3580013/should-i-use-past-or-present-tense-in-git-commit-messages?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa) (imperative) for your commits.

E.g "Make dog bark" (imperative) vs "Makes dog bark" or "Made the dog bark"

> Describe your changes in imperative mood, e.g. "make xyzzy do frotz" instead of "[This patch] makes xyzzy do frotz" or "[I]
> changed xyzzy to do frotz", as if you are giving orders to the codebase to change its behavior.
_github_

## Dig a little deeper
Identify what questions you have about GitHub. Craft your question and do some exploration.
And if you're still hungy, check out [Atlassins tutorial](https://www.atlassian.com/git/tutorials/saving-changes). Its fairly comprehensive so be sure to keep your focus within the scope of the learning competencies. .

Do you know how to check your commit history? Would you know where to look in each message to find what files were changed?
What do the terms working and staged mean?


## Tracking Changes

Whenever you change the state of a file, it is tracked. You can check the status of all the files in the local repo by typing `git status` . If you have modified any files you will see some categories: Changes not staged for commit:, Changes to be committed:, and if you have created a new file, Untracked files:. No changes would return the message:

`On branch master
nothing to commit, working directory clean`

You can only push changes that have been committed.

Git also gives you handy instructions below these categories. In untracked files it tells you how to add the files (use "git add <file>..." to include in what will be committed) from untracked to staged(changes to be committed), and how to remove a file from the added section to bring it back to untracked (use "git reset HEAD <file>..." to unstage).

If you commit some files and decide that you actually want to change the files, use the command:

`git reset --soft HEAD^`

HEAD is the commit you are currently on, HEAD^ is the last commit, HEAD~3, HEAD~4, HEAD~5, are the 3rd 4th and 5th commit from HEAD respectively.

## Release 3: Make Changes

Now you know about how git tracks changes, so it's time to make some changes! Make sure you are on the `master` branch for this. If you were on the `git-playground` branch, type `git checkout master` to go back to your master branch.

- Using Sublime, open the [my_reflection.md](my_reflection.md) file associated with this challenge
- Answer the first question in the reflection file - make sure to save your file
- Check your git status
- Write something in this README.md
- Check your git status (notice a pattern?)
- Add the change you made in the my_reflection.md to the stage
- Unstage the change for my_reflection.md
- Add and commit the changes for my_reflection.md
- Check the git log to see your commit and message
- Reset the last commit
- Add and commit the changes for my_reflection.md again

## Release 4: Pushing Changes

Now it's time to make your changes live on GitHub. There are two ways to do this. The first is the faster way, and the second is by [making pull requests](making-pull-requests.md), which is highly favored when working with teams. You can choose which you would like to do. We are outlining the faster version below, but we highly recommend taking a look at the process for making pull requests as well to get a feel for it.

Before you can push your changes up, you'll want to make sure you don't have different versions of your repository locally and remotely. Pull changes from the remote to your local copy by typing:

`git pull origin master` #pull fetches changes and merges them. You can also fetch and merge separately if you prefer.`

Since you've been working on the master branch this entire time, it's easy to push changes to the master branch on GitHub. Simply type:

`git push origin master`

`origin` refers to the remote location (in this case your repository on Github), and `master` is the branch you want to push to.

Go to your fork on GitHub to see your changes live!

## Release 5: Reflect
Go ahead and answer each of the questions in the my_reflection.md file (using Sublime). Add your changes and commit them. Make sure you make a great commit message when done with this challenge. Don't forget to push your changes!

## Release 6: Practice
Remember the reflection you did for the first couple of challenges on the [command line](../1-command-line) and [thinking about time](../3-think-about-time)? Go through the workflow to edit the reflection files for each challenge to add your answers.
