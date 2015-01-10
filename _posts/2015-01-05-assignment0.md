---
layout: post
title: "Assignment 0"
author: nnagle
draft: true
modified:
excerpt: "Intro to R, Rstudio, and Github"
tags: [assignment]
---

This tutorial is liberally adapted from the one [here](http://stat545-ubc.github.io/block000_r-rstudio-install.html).

 - [Why R?](#why-r)
 - [Why Git?](#whi-git)
 - [Installing R](#installing-r)
 - [Installing Github](#installing-github)
 - [Setting Up Git for the first time](#setting-up-git)
 - [Setting up your class workspace](#setting-up-workspace)


## <a name='why-r'>Why R?</a>
 - R is free
 - R is powerful.  Chances are good you can find R code to do whatever cool analysis it is that you want to do.  More so that for any other single software  package.
 - R now has resources to help you create fully reproducible research.  Reproducible is good: for transparency to others, and perhaps more importantly, to save yourself time the next time.

## <a name='why-git'>Why Git (Version Control)?</a>
 - Sometimes you follow a dead end.  VC help you to rewind.
 - VC help you to share with others.  For example with your instructor or TA :)
 - It's so much more flexible and precise than something like "track changes" in Word.


## <a name='installing-r'>Installing R</a>

 - Install [R, a free software environment for statistical computing and graphics](http://www.r-project.org).  Once you install R, make sure it opens up smoothly.  Once you've done this, you shouldn't have to access R directly again during this class.
 - Install [Rstudio, a powerful and productive user interface for R that is free](http://www.rstudio.com). Follow the links to the open source desktop version.  You might even check out the [Preview Version](http://www.rstudio.com/products/rstudio/download/preview/), which includes all kinds of neat stuff, such as the ability to create MS Word notebooks (if that floats your boat.  It doesn't float mine.  But I still use the Preview Version because of all the other cool stuff!).  Rstudio provides really helpful tools like a text editor, and data and file browsers.  Rstudio can also integrate with Github, however it can't do all Github tasks, so you'll still need to install Github (described below).

Test it:

 - Fire up Rstudio.
 - Writing code is like any other writing process: there is way more drafting than there is final writing.  Put your cursor in the "Console Window."  I treat the Console window like a "drafting" book.  It's where I sketch out ideas, and R lets me know if she understands them.  Type something like:
 ```r
 x <- 2+4
 ```
Now inspect the `x` object by typing `x` followed by return.  

You're a coder! If the Console is for sketching code ideas, then the final draft goes in `.R` scripts or in `.Rmd` documents.  More on this later.

Rstudio has a [page for help topics](https://support.rstudio.com/hc/en-us/categories/200035113-Documentation)

## <a name='installing-github'>Installing Github</a>

- Register for a free github account.  You can either go the [public way](https://github.com) or the [education way](https://education.github.com).  Either works for this class.  Pick a username that won't embarrass you in a few years.  Both ways give you unlimited public *repositories* (For now, you can think of a repository as a "project").  The student account gives you a small number of private repositories, which you would normally have to pay for.  In this class we'll use public repositories because it's important for you learn about sharing and attribution.  ([Bitbucket](http://www.bitbucket.org) is a competitor to github that I have also used.  Bitbucket gives academic users free public repositories.  Yay!  Just sayin.)
- Install a git client.  I recommend either the Github client ([Windows](http://windows.github.com) and [Mac](http://mac.github.com)).    A Git client is to Git what Rstudio is to R.  It makes life a little easier.

## <a name='setting-up-git'>Setting up git for the first time.</a>
- The first time using git can be a pain.  ASFAIK, you can not use git for the first time in Rstudio.  Rstudio expects that git is already set up.  You should use github to initialize git.
- When you first setup Github (if that's what you go with), it will ask you for your git username and email. Do this.  You should be good to go!

## <a name='setting-up-workspace'>Setting up your class workspace</a>
For this class, you will maintain a repository with your assignments.  When you want help (and you will want help at some point), you can share your repository with the TA or me, and we see exactly what is happening.

When you want to turn in your homework, you just copy your work to our repository.  Again, we can see what you did.  No emails to get lost.  Additionally, you can see what your colleagues are doing.  I think this is a good thing.  As long as you give credit where credit is due.  If you think you deserve mad props for someone's work let us know.

You will have two repositories.  One which belongs to you, and where you do all your work, and one which belongs to the TA and myself, which is where you submit your work when you are done.  I've already created my repository.
- Go here to the [class github page] (https://github.com/UTK-geog415-s15).
- Find repository with your netid and click to open it up.
- The repository is nearly empty, the only thing there is an empty README.md file.
- In the upper right, click the `Fork...` button.  "It should only take a few seconds."  You will now have a copy of the repository in your own github home.  The windows browser will probably have ejected you from the class account to your own account.  You should see you own version of the repository now.  There are now two copies of the repository, one called `UTK-geog415_s15/netid` which belong to me, and one called `[your user name]/netid` which belongs to you.

You will do all of your homework on **your** repository, and when you are ready to submit your homework, you will send me a *Pull Request* so that I can save it on the **class** repository.  This is what I will grade.

The repository is now on your github account but it isn’t on you computer.  The first time only, you need to *clone* it to your computer.

- Open up a terminal or command console.  The easiest way is to open Rstudio, and then click `Tools -> Shell...`.
- Make sure your computer can find git.  type something like `git --version`
- If you have trouble, then it’s probably the case that git is somewhere unusual on your computer.  Look [here](http://www.molecularecologist.com/2013/11/using-github-with-r-and-rstudio/) for help.

### Method A: Clone in Rstudio
- In R, select `File -> New Project… -> Version Control -> Git`
- Paste in the ssh url (it’s still in your clipboard, right?)
- It will probably automatically select your net id as the Project directory name.
- Choose the location on your computer where you want to put this folder.
- Select Create Project

### Method B: Clone from the shell
- Inside the shell, browse over to where you want to put your directory.
For example, on a Mac, you might do something like: `cd ~/Documents/`
On a PC, you might do something like: `cd C:\Users\username\`
- Now, clone your file. Hopefully that ssh url is still in your clipboard, if so, then enter
`git clone ssh.url`

Hopefully that worked.  
Now, back in R, select File -> New Project… -> Existing Directory
and choose your github folder (the one with your netid) as the directory.
Select Create Project.


You now have R and Git setup.  yay!!  Give yourself a pat on the back, crack your knuckles and we can get started with the assignment :)


 ## Homework 0:
 
 Edit your README.md file and write a short bio about yourself.  You can edit it from within R, or using any text editor (like notepad or textedit).  Tell me a bit about your background.  Maybe something about your academic and career goals?  Maybe something memorable about you?  Maybe you love to write haiku?  It’s your space.  Do with it as you wish.

 When you are done with your bio, *commit* your work to the repository.  Even if your text edit has autosave, commit is different.  Commit is like taking a snapshot.  You can always return to the state of a repository at a commit snapshot, even if you later change or delete your file.


#### Commit - Method A: In R

 - In R Click `Git -> Commit`
 - In the upper left, you will see a window of every file that has changed.  Some files are new and should be added, some files are modified and should be checked in.  Select the box next to each file to approve the change.  The files are now
 *staged* to be committed.  You need to write a short message describing the commit.  Something like “added bio to README.md."
 - Click Commit.

 You made the snapshot, but it is still on your computer and not on your github.  You need to “push it” to your github repository.  Click the `push ` button.

 That’s it.  Every so often, remember to commit your changes and push them to the github repository.

#### Commit - Method B: In the shell

 - Type `git status`
 This will tell you what needs to be staged.
 - Enter `git commit -a -m 'helpful meesge explaining what you did'`
 - Enter `git push`  (If that doesn't work try `git push origin master`, and enter you username and password if prompted)


 ### Turn it in
 
 When you’re ready to turn your homework in:
 On the right, click `Pull Requests` -> `Create  pull request.`  
 You’ll see a page which shows all of the differences between your version of the repository and my version of the repository.  Just click once again on `Create Pull Request.`  You can create a message for the pull request.  Something helpful like "[your netid] Homework 0” would be great.

 Click yet once again on Create Pull Request.
 I’ll automatically get a message telling me that you want me to load your repository.  You can view it on the class repository if you want, to make sure it worked.  You’re done.  Now my work begins :)



