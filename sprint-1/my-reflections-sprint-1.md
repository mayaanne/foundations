#My Reflections - Sprint One 



In addition to the challenge specific refletions, answer the following questions (in addition to the challenge-specific questions) in your reflection:



* What parts of your strategy worked? What problems did you face?
* Did you learn any new skills or tricks?
* How confident are you with each of the Learning Competencies?
* Which parts of the work did you enjoy?
* Which parts of the work did you find tedious?



*Command Line Primer (aka Terminal, Shell, Prompt)

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


*Version Control with Git - Primer

1.	Whats the difference between git and GitHub?
Git is a revision control system, a tool to manage your source code history as well as allow many people to collaborate on the project together.
Github is a hosting service for Git repositories.

2.	Can you think of an analogy to describe them?

3.	Did you stick to the timebox suggestions? If not, why not?
Reflection time took more than 30mins. not sure an analogy to describe them.

4.	Any surprises or anything you'd like to share (e.g. Super useful resources)
Git and Github for Poets video was so useful video to understand Gid and github.

*Install and Explore Git

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

*Branch, Pull, Merge Primer

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

*GitHub Fork & Clone Curriculum Challenge

1. What are some examples of when you would fork?
Forks are used to either propose changes to someone else's project (ex,bug's fixes)or to use someone else's project as a starting point for your own idea.

2. Write your own step-by-step fork and clone instructions. Describe what you did.
 Origin: https://github.com/dev/foundations
Destination: https://github.com/miju-cho/foundations

FORK FROM ORIGIN
1.On Github, navigate to the dev/foundations repository. In the top-right corner of the page, clich Fork button 
(Forking a dev/foundation repository allow me to freely experiment with change without affecting the original project)

FORKED REPO IN DESTINATION
2.On Github, navigated to miju-cho/foundations repository
click Setting and issues.
3.Under the repositoryname, click CLONE or DOWNLOAD
4.In the Cone with HTTPs section, click to copy the clone URL for the repository.
5.Open terminal
6.Type "git clone", and then paste the URL you copied. It will look like this:
$git clone https://github.com/miju-cho/foundations
7.Press ENTER. Your local clone will be created.

Did you have any moments where it all clicked? What clicked?
Stage your file.

*Git Set Remotes and Merge Primer

What is the difference between cloning from a forked and cloning from a non-forked repo.

Can you think of an analogy to describe forking?

What is a remote?
-A remote in Git is a common repository that all team members use to exchange their changes. In most cases, such a remote repository is stored on a code hosting service like GitHub or on an internal server -Git tower-

Did anything surprise you?

*Git - Setting Remotes and Syncing Forks Challenge

What is a remote?
-A remote in Git is a common repository that all team members use to exchange their changes. In most cases, such a remote repository is stored on a code hosting service like GitHub or on an internal server -Git tower-

How are they set up?
-Add a new remote, fetch, and check out a branch from it

$ git remote
origin
$ git branch -r
  origin/HEAD -> origin/master
  origin/master
$ git remote add staging git://git.kernel.org/.../gregkh/staging.git
$ git remote
origin
staging
$ git fetch staging
...
From git://git.kernel.org/pub/scm/linux/kernel/git/gregkh/staging
 * [new branch]      master     -> staging/master
 * [new branch]      staging-linus -> staging/staging-linus
 * [new branch]      staging-next -> staging/staging-next
$ git branch -r
  origin/HEAD -> origin/master
  origin/master
  staging/master
  staging/staging-linus
  staging/staging-next
$ git checkout -b staging staging/master
...
-from https://git-scm.com/docs/git-remote-

How would you explain a remote to a non-technical person using an analogy?
-A remote in git is basically a bookmark for a different repository from which you may wish to pull or push code.
The bookmarked repository may be on your local computer in a different folder, on remote server, or it may even be the repository itself ( I haven't tried this ) but the simplest analogy is a bookmark.

Add, commit and push your reflection.

*Setup new Repo & Create Blog Challenge

Reflect on this sprint. What did you learn about your learning? it was okay.
What surprised you? 
-somehow I had thought that I need to clone the URL of https://github.com/mijucho/mijucho.github.io.git to my under the mijucho.hithub.io so I had a this problem "override r--r--r-- chomiju/staff for mijucho.github.io/.git/objects/pack/pack-56244704efe495a909f082cf78b04c37673ef9b8.idx?" but after use "rm -rf /your/path" the problem was solved.

Add, commit and push!

*Thinking like a Programmer

Describe the process for solving problems
1.Understand
Know exactly what is being asked. Most hard problems are hard because you don’t understand them (hence why this is the first step).
2.Plan
Don’t dive right into solving without a plan. Plan your solution!
3.Divide
Break it into sub-problems. These sub-problems are much easier to solve.
.Debug: Go step by step through your solution trying to find where you went wrong. Programmers call this debugging
.Reassess: Take a step back. Look at the problem from another perspective. 
.Research: No matter what problem you have, someone has probably solved it.(Google)
4.Reflect
reflection is a the most important aspect of learning.
Keep Practice. Practice. Practice!!

How will you integrate this idea?
I would like to apply this process of problem solving while I am Jurney through the DEV.

What did you learn about flipped classroom?
A flipped classroom is one where students are introduced to content at home, and practice working through it at school.Students watch pre-recorded videos at home, then come to school to do the homework armed with questions and at least some background knowledge.

The concept behind the flipped classroom is rethink when students have access to the resources they need most. If the problem is that students need help doing the work rather than being introduced to the new thinking behind the work, than the solution the flipped classroom takes is to reverse that pattern. This will increasing the opportunity for personalization and more precise guiding of learning. 


*Introduce yourself and get to know your cohort

 I was use to introduce myself as my kids' mum. So it wasn't use to introduce myself to others. However it was good time to think about myself. ^^