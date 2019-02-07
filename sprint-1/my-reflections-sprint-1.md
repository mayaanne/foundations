# My Reflections - Sprint One 

## Version Control
 **_What's the difference between Git and GitHub?_**
 
   Git is a version control software, a local platform from which you can edit a piece of work multiple times and have the ability to view the history and the version of each different edit. Hence, Version Control. GitHub is a web platform that uses Git and allows users to work collaboratively and simultaneously on the same project without altering or damaging one another's work.

 **_Can you think of an analogy to describe them?_**

   It is an individual vs a group scenario. Think team sports: a netballer trains at home everyday for an hour to become the best player she can be (Git). When the time comes to play ball, her team comes together, after having performed their own individual training tasks at home as well (Git + GitHub), and together, they function cohesively without ever tripping one another up (GitHub). 
   
 **_Do you think you would still remember the difference a week from now if you didn't revisit the material?_** 

   Probably not. Does anyone remember anything if they don't revisit the material? Maybe only in the case of fight and flight, but that certainly isn't happening today.

 **_Did you stick to the timebox suggestions? If not, why not?_** 

   I was better this time around than during the previous task (Command Line Primer). I only ran about 30 minutes over (I really struggled with the analogy question above), and that's because I checked in with Toggl every so often to see how I was running for time.


## Exploring Git
 **_What is a GitHub work flow?_** 

   A GitHub work flow is the process through which a project is created and completed--from start to finish, and with all of the edits in between. Created using Git software, it is then stored and made accessible to edit and view on GitHub. (…right????)

 **_What did you notice about your own learning? What did you do when you were confused or blocked?_** 
 
   I was blocked MANY, MANY TIMES. When I got stumped, taking a break before returning to the task usually helped to clear my head. I tried not to simply guess any of the answers to the quiz questions because I wanted to know how the solution was reached--otherwise, I wouldn't know for next time! It's been a long time since I have studied anything and I know that we are only two days in but so far, I have been surprised by my own diligence. Having said that, I've also been feeling mighty slow and almost stunted in comparison to the rest of my cohort, who seem to have breezed through this step MILES ago. 

 **_Is there anything you'd do differently if you were to repeat the learning exploration again?_** 

   Use Google more to help me out. I often ended up stuck along the way because my computer responded differently to the way the lesson plan predicted. Instead of simultaneously looking to Google for help, I only reached out to the EDA peeps and ended up wasting mucho time in waiting for them to reply.


## Track and Commit
 **_How would you describe stage and commit to your non-tech savvy friends?_** 

   A simpler way to think of the term __commit__ is to replace it with the word _save_. As you go through your project, you are able to _save_ each edit that you make. This means that you are able to access every single different version that you have created along the way. You can also revert the project back to a previous edit if you decide that it is better than the current one. In coding, this is imperative because it allows you to return to a previous _saved_ version of the code, should, for example, a bug arise in the updated version that needs to be found and fixed. 

   Let's say I was writing a piece of prose. By __committing__ (_saving_) each version as I go, I am able to access all of the previous versions of my piece without having to search through various files or lose the content altogether (because of the backspace button, my old friend). I can also go back to an older version and start fresh if I decide that it is more lyrical and prose-like than the current one. 

   __Staging__ is the step that comes before __committing__ (_saving_) the updated file. It allows you to test the update before __committing__ (_saving_) it.


## Branch, Pull, Merge
 **_What is master?_** 

   Master is the main source of code--the final product, if you will--with which users interact.

 **_Why create a branch?_** 

   Creating a branch allows you to 'branch off' from the master copy of work so that you can change and update features without affecting the master itself. Only once the branch has been pulled and merged will it make changes to the master.

 **_Do the concepts feel intuitive or difficult to understand?_** 

   I don't think that 'intuitive' is the word I'd use. I guess that _Master_ and _Branch_ make sense well enough, but add all of the commands into the mix and I would say DIFFICULT, definitely difficult.


## GitHub Fork & Clone
 **_What are some examples of when you would fork?_** 

   Specific examples? Unsure, as yet. I imagine that any instance in which I see an improvement that can me made in a master branch is a time when I would fork the repository, make the changes in my own branch and then create a pull request for my improvements (if they are, in fact, improvements) that can then be merged with the master branch (with the maintainer's approval).

 **_Write your own step-by-step fork and clone instructions. Describe what you did._** 

 1. On GitHub, fork the repository from the origin user to your own account.
   2. From your fork, go into settings-->options-->issues and make sure the issues box is selected. 
 3. Click the clone button and copy the URL.
 4. Switch over to your terminal. Ensure that you are in the correct folder (in which you want the forked repository to be saved) before continuing. Once you are in your preferred folder, enter the __git clone__ command and paste the URL. Hit enter.
 5. Once it has finished loading, navigate into the cloned repository. You will know that you are in it because it will say __(master)__ beside your username.

 **_Did you have any moments where it all clicked? What clicked?_** 

   I definitely understood __forking__ more than __branching__. In the previous __Branch, Pull Merge__ challenge, I actually __forked__ the file rather than __branching__ it. I don't know how I'd have __branched__ it. Do I not know how to __branch__?? Ughhhhh. Brain. 

   Anyway, whilst it looks as though __branching__ may have fallen flat, __forking__ seemed to click--which is surely deserving of a 'that's what she said' joke...?


## Set Remotes and Sync Fork - Primer
 **_What is the difference between cloning from a forked or non-forked repo?_**
   
   Cloning from a forked repo allows you to propose changes to someone else's project without changing their master branch. Cloning from a non-forked repo allows you to use someone else's project as a starting point for your own idea--copy someone else's art and make it better.

 **_Can you think of an analogy to describe forking?_**
   
   An analogy for forking? Gahhhhh I'm just about out of analogies... Forking is perhaps a bit like playing Chinese Whispers. A message is passed around the circle (the fork) and though the message often changes by the end (the commits), the person who started the chain (the owner) still holds the original message (the master) and is able to tell the group whether their end result was right or wrong (whether the commits will be merged or not).

   Yup, that's all I got.

 **_What is a remote?_**

   A remote has nothing to do with the television or the aircon, as I had first imagined. When it comes to coding, a remote--short for remote URL (makes more sense when you say it in full, no?)--is simply a place where your code is stored...remotely.


##  Setting Remotes and Syncing Forks - Challenge
**_How are remotes set up?_**

   I don't know how to answer this question and I am not going to do you the disservice of trying to BS my way through it. All (I think) I know is that when you clone a forked repository to your local computer, the forked repository becomes the remote. I think. As I said, I don't know. You're going to have to tell me.

**_How would you explain a remote to a non-technical person using an analogy?_**
     
   A remote is like a Spotify playlist--think of it as a place where you can store your music. When Spotify adds new playlists, you can download them onto your phone and store them there for future use, add select songs to your own playlists, and make general changes to your account. Although, are you so non-technical that you don't use Spotify? ...I think my analogies are getting worse.

**_How many times did you feel like "oh God I don't understand this"?_**
    
   Honestly? When I have to answer these reflection questions and I realise that I have no idea how to define a certain concept. I can kind of make things happen but I don't really know how I do it, and replicating the proces--even if only a half a day later--often proves to be quite, quite difficult. And then there's these analogies. Maybe I don't know enough about the world to know what could relate to what in any semblance of a sensible way [insert shrug emoji here].


## Setup new Repo & Create Blog Challenge
**_Reflect on this activity. When did you feel frustrated?_**
   
   Do you want to hear something wonderful? I DIDN'T! I've been looking forward to this step the whole sprint because creating is what I love to do and website design is what I want to segway into, and I guess this challenge allowed me to pretty much do both! Even if I had been stuck somewhere during this challenge, I wouldn't have felt frustrated as I have previously because I knew that the end result was going to be the first step in the direction of my dream (?) career. (Okay, _dream_ might be a bit of a stretch. In that world, I'd probably be a writer or a singer or a _very_ well-paid intrepid traveller.)

**_If you didn't already know that this is the way websites are made; was it what you pictured? How does the reality of this process differ from your preconceptions?_**

   Is this what I'd been picturing? No, I don't think that I'd been picturing anything. When I think of what creating a website looks like, I think of Wordpress. This process differed from my preconceptions in that I thought it'd be impossibly difficult to create a website. But look! I did it! And I guess that if I can do it, then shoot--anyone can. 


## Thinking Like a Programmer
**_Describe the process for solving problems._**

   Dev-Academy provides a 10 step approach to solving problems. The most important of which––I believe––is to BREATHE. Something I'm working on. Anywayyyyyy, the first step is to get in the zone––one spawned from habit rather than fantasy. Start the timer––timeboxing is everything! Break the question down into something clear and easy to understand. If you don't understand the question, then you won't solve the problem unless you miraculously stumble upon it (which happens, sometimes, but not as often as one would like). PLAN PLAN PLAN. Don't just dive into the water all gung-ho. Check for hazards first. Break the problem up into smaller parts and try solving these smaller equations first. As you solve the smaller parts, begin broadening the picture and put the puzzle pieces together in an attempt to reach an overall solution. If you get stuck, BREATHE. IN. OUT. Walk away if you have. Literally––walk, and don't stop walking. Don't return to the problem until you have a clear head and a calm mind. Remember the difference between curiosity and irritation. Upon solving the problem, find a way to improve it. Make it simpler, clearer, easier to follow along with and replicate. Reflect on your process and your progress. And then practice. Practice. Practice. You want to learn Spanish? Get on Duolingo twice a day, baby. 

**_Will you follow that process? How?_**
   
   The four questions? Already on it. The hardest part for me to enact will be the planning aspect. I've never been much good at that. I prefer to throw myself into something and figure it out along the way. I'm starting to understand that this frame of being might not work so well in the coding realm. I'll do my best to follow the process, and to breathe. DEFINITELY need to breathe. 

**_What did you learn about the flipped classroom?_**
   
   Firstly, that it isn't actually a synonym for flipped learning. The two concepts are different concepts. The idea of a flipped classroom is that you do the learning at home (video tutorials, online articles, step-by-step online courses) and the homework at school (asking questions and solving problems with the teacher). Flipped learning, I find to be a little more confusing...I think it's just that rather than being in a classroom where the teacher is talking AT you, you're in a classroom where the teacher is available to assist with problems and nudge you in the direction of the correct answer without just handing it over. 


## In addition to the challenge specific reflections, answer the following questions in your reflection:


- What parts of your learning strategy worked? What problems did you face?



- How confident are you with each of the Learning Competencies?



- Which parts of the work did you enjoy?



- Which parts of the work did you find tedious?



- Did you hear a self critical voice in your head throughout the process of learning during this sprint? What did it say to you? Do you believe what it said?