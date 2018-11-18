[Sprint 1 Home](README.md)|
---| 

# Version Control with Git - Primer

### Learning Competencies
By the end of this exploration, you should be able to 

- Explain what version control is and does  
- Understand what Git is 
- Understand what GitHub is

## Summary 

Version Control allows groups of people to work together on the same code, at the same time, without overwriting each others work. It is not JavaScript, or Ruby, or C#. It is software that you download - a form of distributed version control which means it manages changes to a project without overwriting any part of the project.

## Timebox

Activity | Time|
------------|----------|
Watch | 5 minutes
Explore | 30 minutes |
Reflect | 30 minutes |

Follow the timebox suggestions. This is a primer only and there is a deep dive challenge next to start applying this knowledge. Let the learning competencies be your guide.

## Description 

Version control enables Web Developers to collaborate without over writing each others work, and provides an entire history of changes. 

__The most widely used Version Control Software is called Git__

Git doesn't require any remote servers for its operation (it can simply be installed on your computer), but for easy access and collaboration, web developers use GitHub (the largest code host on the planet) for storing and sharing code.

__GitHub is a company that provides file hosting online.__ 

With over 10 million users, GitHub has become a social network for web developers - much like facebook or twitter. You build a profile, upload projects to share and connect with other users by following their accounts. And while many users store programs and code projects, there’s nothing preventing you from keeping text documents or other file types in your project folders to show off.

__So to conclude, Git is a (software) tool that you download and GitHub is a service that you sign up to.__

Almost all of your learning material will use Git, and almost all of it will be distributed via GitHub. 

## Watch
[What is Git and GitHub](https://www.youtube.com/watch?v=uUuTYDg9XoI) 

_Pro-tip click on the video settings wheel to speed up online tutorials_

## Explore
Explore what is Version Control?   
What is Git?  
What is GitHub?   

Have a look around the internet. Let the learning competencies at the top of the page be your guide? Take notes. Keep within the time frame. 

Suggested Resources:  
[Udacity's Version control (recommended)](https://www.udacity.com/course/version-control-with-git--ud123)  
[Code Schools Git Real](https://app.pluralsight.com/player?name=6eec00f4-f910-4efc-9698-936948026502&mode=live&clip=0&course=code-school-git-real&author=gregg-pollack)  
[Git and GitHub for Poets](https://www.youtube.com/watch?v=BCQHnlnPusY)   
Git Resource - below  

## Reflect
On a text document, record your reflections. You'll transfer these reflections to a git file in a later challenge.  

__In your reflection answer the questions:__
1. Whats the difference between git and GitHub?
2. Can you think of an analogy to describe them?
3. Did you stick to the timebox suggestions? If not, why not?
4. Any surprises or anything you'd like to share (e.g. Super useful resources)


## Git Resource

#### Why use Git

Without Git or another form of version control system (VCS), being a web developer would be significantly more painful day to day. Using a VCS is extra work, and the advantages aren't always obvious. But trust us, Git is a very powerful (and essential) tool for collaboration.


#### How Git works

With Git, each project has its own repository - a collection of all the versions of the project along with some special information - What order the changes occurred; A description of each change; who was responsible for each change etc.

Git doesn't automatically keep track of your versions - You have to explicitly tell it when you are finished so that Git will track them for you. **The act of telling Git that the version is finished is called committing**. Much like you would commit something to memory, you also commit changes into your repository. Because of this, versions are often referred to as commits. In many cases, it doesn't make sense to treat unfinished work as a version. But in others, a commit might simply be a spelling correction or a fix to a broken link.

Most of the time when you interact with your project, the complexity is hidden so that you won't even know it is there until you need to interact with it. Git has a set of tools to review your project history - For example, providing you the ability to view or filter the full list of commits, or even switch what version your project is currently displaying. Want to go take a look at what your project
looked like this time last sprint, last month, last year? Git will let you do all of those things and more, often with just one command.

#### Words people use when they talk about Git
*Shared via [Readwrite.com](http://readwrite.com/2013/09/30/understanding-GitHub-a-journey-for-beginners-part-1)*

`Command Line:` The computer program we use to input Git commands. On a Mac, it’s called Terminal. On a PC, it’s a non-native program that you download when you download Git for the first time. In both cases, you type text-based commands, known as prompts, into the screen, instead of using a mouse.

`Repository:` A directory or storage space where your projects can live. Sometimes GitHub users shorten this to “repo.” It can be local to a folder on your computer, or it can be a storage space on GitHub or another online host. You can keep code files, text files, image files, you name it, inside a repository.

`Version Control:` Basically, the purpose Git was designed to serve. When you have a Microsoft Word file, you either overwrite every saved file with a new save, or you save multiple versions. With Git, you don’t have to. It keeps “snapshots” of every point in time in the project’s history, so you can never lose or overwrite it.

`Commit:` This is the command that gives Git its power. When you commit, you are taking a “snapshot” of your repository at that point in time, giving you a checkpoint to which you can reevaluate or restore your project to any previous state.

`Branch:` How do multiple people work on a project at the same time without Git getting them confused? Usually, they “branch off” of the main project with their own versions full of changes they themselves have made. After they’re done, it’s time to “merge” that branch back with the “master,” the main directory of the project.

#### Git-Specific Commands
*Shared via [Readwrite.com](http://readwrite.com/2013/09/30/understanding-GitHub-a-journey-for-beginners-part-1)*

Since Git was designed with a big project like Linux in mind, there are a lot of Git commands. However, to use the basics of Git, you’ll only need to know a few terms. They all begin the same way, with the word `git`.

`git init:` Initializes a new Git repository. Until you run this command inside a repository or directory, it’s just a regular folder. Only after you input this does it accept further Git commands.

`git config:` Short for “configure,” this is most useful when you’re setting up Git for the first time.

`git help:` Forgot a command? Type this into the command line to bring up the 21 most common Git commands. You can also be more specific and type `git help init` or another term to figure out how to use and configure a specific Git command.

`git status:` Check the status of your repository. See which files are inside it, which changes still need to be committed, and which branch of the repository you’re currently working on.

`git add:` This does not add new files to your repository. Instead, it brings new files to Git’s attention. After you add files, they’re included in Git’s “snapshots” of the repository.

`git commit:` Git’s most important command. After you make any sort of change, you input this in order to take a “snapshot” of the repository. Usually it goes `git commit -m “Message here”`. The -m indicates that the following section of the command should be read as a message.

`git branch:` Working with multiple collaborators and want to make changes on your own? This command will let you build a new branch, or timeline of commits, of changes and file additions that are completely your own. Your title goes after the command. If you wanted a new branch called “cats” you’d type `git branch cats`.

`git checkout:` Literally allows you to “check out” a repository that you are not currently inside. This is a navigational command that lets you move to the repository you want to check. You can use this command as `git checkout master` to look at the master branch, or `git checkout cats` to look at another branch.

`git merge:` When you’re done working on a branch, you can merge your changes back to the master branch, which is visible to all collaborators. `git merge cats` would take all the changes you made to the “cats” branch and add them to the master.

`git push:` If you’re working on your local computer, and want your commits to be visible online on GitHub as well, you “push” the changes up to GitHub with this command.

`git pull:` If you’re working on your local computer and want the most up-to-date version of your repository to work with, you “pull” the changes down from GitHub with this command.



