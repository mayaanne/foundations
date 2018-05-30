[Week 1 Home](../)

# Git - Setting Remotes and Syncing Forks Challenge

### Learning Competencies
By the end of this challenge, you should be able to:

- Set up remotes in your forked repostory
- Fetch changes 
- understand how to keep forks in sync. 

## Summary
When we make important updates to the curriculum (on our repo), you'll need to tell Git how to get those changes. 
You'll do this by a by setting remotes, fetching and at mergining into your own copy. 


## Exploration and Application

Exploration | Time to box |
------------|----------|
Intro and exploration| 40 miinutes
Add an upstream | 10 minutes
Fetch changes | 10 minutes 
Reflect | 15 minutes |

Follow the time box suggestions. If you get stuck, take a quick break and come back to it. Reach out to the community on slack. Remember to clarify and define what you are trying to do/solve. Break it down into steps

## Pre-Requisites:
To complete this deep dive, you should have completed all previous git/GitHub hub primers and challenges. 

## Intro 
As a web developer you'll be working 90% of the time on a local version of a code base, using a text editor (like visual studio or sublime) to create and edit code. But what use is that if it lives only on your computer? You'll need to be able to contribute to codebases and keep your local versions in sync. 

You can do this by setting remotes.

Explore a litte and about remotes. Don't get too side tracked by branches. Begin by identifying what is it your trying to understand? Check the learning objectives. If you need a little extra guidance  here's a couple of links to help you along: 

[GitHub - configure git to sync with your fork part one](https://help.github.com/articles/fork-a-repo/#step-3-configure-git-to-sync-your-fork-with-the-original-spoon-knife-repository)
[GitHub - syncing a fork part two](https://help.github.com/articles/syncing-a-fork/)
[Upstream and downstream - stackoverflow](https://stackoverflow.com/questions/2739376/definition-of-downstream-and-upstream)
[Managing remotes](https://help.github.com/categories/managing-remotes)

In the next step we'll be asking you to set an 'upstream' so you can 'fetch' any changes that are currently in our version. 

__Pro-tip__ `Upstream` is a naming convention. We don't recommmend using any other name, but for comparisions sake I've added 3 remotes to illustrate that the remote (usually named upstream) is simply where we want to fetch changes from and push contributions to. 

<figure>
  <figcaption>
    <p><strong>Figure 1:</strong> Adding variations of upstream remotes to local repo</p>
  </figcaption>
  <img src="../../images/github_11_remote.png" alt="adding remotes"><br>
</figure>



## Add an Upstream
1. Add an upstream to your local version


## Fetch Changes 
You're going to be fetching changes from our remote sever (and therefore our version of the repo). Its important to know that Git will not over-write your work. Git will ensure everything is kept if your files and our files are different and Git will ask you to manually decide which parts you want to keep. 

1. Check to see if there are changes on the upstream remote?
2. If there are, fetch them

## Merge Changes 
1. Merge changes


## Reflect
Edit your my_reflection.md file. 

Reflection on:

1. What is a remote?
2. How are they set up?
3. Summarize the purpose of a remote
