[Week 1 Home](../)

# git Remote merge Primer 

### Learning Competencies
By the end of this exploration, you should

- Explain what a remote is

## Summary
Web Developers use tools to track their progress and create backups. GitHub is a popular platform for this, especially in Git uses remote URLs to figure out where to go on the Internet to push and pull files. By setting a remote, you are basically telling git exactly where to go when you want to save (push) your work, get (pull) your work to your computer, or fetch changes from the repo you forked from.

## Exploration and Application

Exploration | Time to box |
------------|----------|
Your forked context | 10 minutes
Give it go online | 10 minutes |
Explore | 20 minutes 
Reflect | 15 minutes |


## Your forked context 
When you began learning git/GitHub, you created a __fork__. 
You then made a copy of that fork on your local computer (i.e. you cloned it).
When you make changes and `git push` them, you are pushing to __your master branch__ of your own __forked repo.__ None of your changes are reflected on __our master__ (which is a good thing) 

__Pro-tip__  Whn you are exploring git work flow, you will come across advice like 'don't push to master'. This is valid advice for when you don't have your own fork (imagine 100 students pushing their changes to our master file -eek!). 

Keep in mind lots of material online are not talking from a forked context. You'll hear terms like 'branch' and 'pull requests' to 'merge' into (their) master. We'll cover that soon.  

Study this diagram, adapted from [GitTower](https://www.git-tower.com/learn/git/ebook/en/command-line/remote-repositories/introduction) (thanks GitTower!). 

<figure>
  <figcaption>
    <p><strong>Figure 1:</strong> Left = YOUR Master, Right = OUR master</p>
  </figcaption>
  <img src="../../images/github_10_fork.png" alt="Fork GitHub Repo"><br>

</figure>


## Give it a go online
 - You could revisit the [Interactive web tutorial](https://try.github.io/levels/1/challenges/1) and this time go through to the last steps. 


## Explore 
You could ask simple questions like "what is a git remote" to be specific, but if you need to understand the bigger picture more you could ask questions like "github user workflow." I googled "what is a git remote repository" and found [GitTower's useful step by step course](https://www.git-tower.com/learn/git/ebook/en/command-line/remote-repositories/introduction)


## Reflect
Open your my_reflection.md file and answer the following 

1. What is the differenc between cloning from a forked and cloning from a non-forked repo. 
2. Can you think of an anology to describe forking?
3. What is a remote? 
4. Did anything surprise you?


