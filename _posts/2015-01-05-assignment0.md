---
layout: post
title: "Assignment 0"
author: nnagle
modified:
excerpt: "Intro to R, Rstudio, and Github"
tags: [assignment]
---

This tutorial is liberally adapted from the one [here](http://stat545-ubc.github.io/block000_r-rstudio-install.html).

## Objective
 - Get your computer setup with R, Rstudio, and Git.
This combination will prepare your for powerful quantitative analysis that is both well archived and reproducible.  In other words, for quantitative analysis that is scientific.

## Outline
 1. Install R.
 2. Install Rstudio.
 3. Test
 4. Install git
 5. Clone the assignment repository.
 6. Makes some changes.
 7. Push it back.


## Installing R

 - Install [R, a free software environment for statistical computing and graphics](http://www.r-project.org).  Once you install R, make sure it opens up smoothly.  Once you've done this, you shouldn't have to access R directly again during this class.
 - Install [Rstudio, a powerful and productive user interface for R that is free](http://www.rstudio.com). Follow the links to the open source desktop version.  You might even check out the [Preview Version](http://www.rstudio.com/products/rstudio/download/preview/), which includes all kind of neat stuff, such as the ability to create MS Word notebooks (if that floats your boat.  It doesn't float mine.  I still use the Preview Version because of all the other cool stuff).  Rstudio provides really helpful tools like a text editor, a data browsers.  Rstudio can also integrate with Github, however it can't do all Github tasks, so you'll still need to install Github (described below).

Test it:
 - Fire up Rstudio.
 - Writing code is like any other writing process: there is way more drafting than there is final writing.  Put your cursor in the "Console Window."  I treat the Console window like a "drafting" book.  It's where I sketch out ideas, and R lets me know if she understands them.  Type something like:
 ```r
 x <- 2+4
 ```
Now inspect the `x` object by typing `x` followed by return.

You're a coder!

Rstudio has help topics [here](https://support.rstudio.com/hc/en-us/categories/200035113-Documentation)

## Installing Github

 - Register for a free github account.  You can either go the [public way](https://github.com) or the [education way](https://education.github.com).  Pick a username that won't embarrass you in a few years.  The public way gives you unlimited public *repositories* (For now, you can think of a repository as a "project").  You have to pay for private projects (repositories).  The student account gives you a small number of private repositories for free.  In this class we'll use public repositories, because it's important for you learn about sharing and attribution.  ([Bitbucket](http://www.bitbucket.org) is a competitor to github that I have also used.  Bitbucket gives academic users free public repositories.  Yay!  Just sayin.)
  - (Recommended, but optional)  Install a git client.  I've used both [SourceTree](http://www.sourcetreeapp.com) and the Github client for [Windows](http://windows.github.com) and [Mac](http://mac.github.com).    I've used both Mac programs.  Sourctree is a little more full-features, but Github may be simpler for a first-timer.  A Git client is to Git what Rstudio is to R.  It makes life a little easier.  But Git isn't as tricky as R, so that's why I have this as optional.
