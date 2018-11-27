[Sprint 1 Home](README.md)|
---| 

# Git Set Remotes and Merge Primer 

### Learning Competencies
By the end of this exploration, you should be able to 

- Explain what a remote is


## Summary
Git uses remote URLs to figure out where to go on the Internet to push and pull files. By setting a remote, you are basically telling git exactly where to go when you want to save (push) your work, get (pull) your work to your computer, or fetch changes from the repo you forked from.

## Timebox

Activity | Time|
------------|----------|
Refresh | 10 minutes
Explore | 60 minutes 
Reflect | 15 minutes |


## Refresh
1. You forked our repo (effectively creating your own version of it). 
2. You made a copy (clone) of that fork on your local computer.
3. You staged changes 
4. You pushed changes to __your__ forked repo. You did so on your own master branch. None of your changes are reflected on our repo. 

__Pro-tip__  When you are exploring git work flow, you will come across advice like 'don't push to master'. This is valid advice for when you don't have your own fork.

Keep in mind lots of material online are not talking from a forked context. You'll hear terms like 'branch' and 'pull requests' to 'merge' into (their) master. We'll cover that soon.  

Study this diagram, adapted from [GitTower](https://www.git-tower.com/learn/git/ebook/en/command-line/remote-repositories/introduction) (thanks GitTower!). 

<figure>
  <figcaption>
    <p><strong>Figure 1:</strong> Left = YOUR Master, Right = OUR master</p>
  </figcaption>
  <img src="../images/github_10_fork.png" alt="Fork GitHub Repo"><br>

</figure>

## Explore 
Explore a little about remotes. Begin by identifying what is it your trying to understand. Check the learning objectives. If you need a little extra guidance here's a couple of links to help you along: 

__Recommended resources:__ 
- [Git tower - Connecting to a remote](https://www.git-tower.com/learn/git/ebook/en/command-line/remote-repositories/connecting-remote-repositories#start)  
- [Forking (GitHub Article)](https://help.github.com/articles/fork-a-repo/)
- [Syncing (GitHub Article)](https://help.github.com/articles/syncing-a-fork/)  
- [Working with Remotes (GitHub)](https://help.github.com/categories/managing-remotes/)  
- [Configure Git to sync with Remote](https://help.github.com/articles/fork-a-repo/#step-3-configure-git-to-sync-your-fork-with-the-original-spoon-knife-repository)  
- [Git Pro - Working with Remotes](https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes)  

## Reflect
Open your `my-reflections-sprint-1.md` file and answer the following. Remember to stage and commit your changes. 

1. What is the difference between cloning from a forked and cloning from a non-forked repo. 
2. Can you think of an analogy to describe forking?
3. What is a remote? 
4. Did anything surprise you?


