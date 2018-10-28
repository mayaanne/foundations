#My Reflections - Sprint One 



In addition to the challenge specific refletions, answer the following questions (in addition to the challenge-specific questions) in your reflection:



* What parts of your strategy worked? What problems did you face?
* Did you learn any new skills or tricks?
* How confident are you with each of the Learning Competencies?
* Which parts of the work did you enjoy?
* Which parts of the work did you find tedious?



Command Line Primer (aka Terminal, Shell, Prompt)
1.	In a couple of sentences, how would you describe the command line in plain english? Can you think of an analogy for it?
A command line is a horizontal line on an interface that you're able to enter           commands that your computer will run for you. 

2.	Did you stick to the timebox guidelines? If not, what change would you make next time? 
I got interrupted by some other staffs while I am doing study, so it took longer than timebox guidelines. I better focus on my study..

3.	Name 5 commands you used, and what they do
mrdir - takes in a directory name as an argument, and then creates a new directory in the current working directory
ls  - lists all files and directories in the working directory
touch - creates a new file inside the working directory
rm -r - deletes a directory and all of its child directories.
 cd -takes a directory name as an argument, and switches into that directory.

4.	Did you learn anything unexpected? Not quite~coz manythings are new anyway..^^


Version Control with Git - Primer

1.	Whats the difference between git and GitHub?
Git is a revision control system, a tool to manage your source code history as well as allow many people to collaborate on the project together.
Github is a hosting service for Git repositories.

2.	Can you think of an analogy to describe them?

3.	Did you stick to the timebox suggestions? If not, why not?
Reflection time took more than 30mins. not sure an analogy to describe them.

4.	Any surprises or anything you'd like to share (e.g. Super useful resources)
Git and Github for Poets video was so useful video to understand Gid and github.
Install and Explore Git

1.	What is a GitHub work flow?
"	Anything in the master branch is deployable
"	To work on something new, create a descriptively named branch off of master 
"	Commit to that branch locally and regularly push your work to the same named branch on the server
"	When you need feedback or help, or you think the branch is ready for merging, open a pull request 
"	After someone else has reviewed and signed off on the feature, you can merge it into master
"	Once it is merged and pushed to 'master', you can and should deploy immediately

2.	What did you notice about your own learning? What did you do when you were confused or blocked?
It takes more time to learn but  I could search other materials if I confused.
So It was good that I could learn my speed of learning.

3.	Is there anything you'd do differently if you were to repeat the learning exploration again? 
I was hurry to finish to each sprint before, I could understand more concept through this time. Well design~

Track and Commit Primer!

1.	How would you describe stage and commit to your non-tech-savy friend?
To push this new file up to github, we first need to stage our changes. 
When staging, you are preparing and organizing a commit.

you're working on two features - one is finished, and one still needs some work done. You'd like to make a commit and go home (5 o'clock, finally!) but wouldn't like to commit the parts of the second feature, which is not done yet. You stage the parts you know belong to the first feature, and commit. Now your commit is your project with the first feature done, while the second is still in work-in-progress in your working directory.

Branch, Pull, Merge Primer

1.	What is Master?
The default branch name in Git is master.

2.	Why create a Branch?
You should create a new branch when your doing development work that is somewhat experimental in nature. So in your scenario definitely create a new branch and not a folder within master. 

3.	Did anything surprise you?
Rebase is quite interesting. 
Git rebase in its simplest form is a command which will merge another branch into the branch where you are currently working, and move all of the local commits that are ahead of the rebased branch to the top of the history on that branch.
o	Move all changes to master which are not in origin/master to a temporary area.
o	Run all origin/master commits.
o	Run all commits in the temporary area, one at a time


