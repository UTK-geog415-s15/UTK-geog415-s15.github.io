---
layout: post
title: "Getting Rstudio to talk to Git in Windows"
author: nnagle
modified:
excerpt: ""
draft: false
tags: []
---

Thanks to David Paulsen for looking this up!

On a computer with Windows and Github, here are some instructions for connecting Rstudio to git.

In Rstudio, Open `Tools -> Global Options -> Git/SVN`

In the Path, select `C:\Users\[username]\AppData\Local\GitHub\Portable_Git_c2[something horrible]\bin\git.exe`


If you can't find the folder `AppData` then you probably need to go into your settings and enable the option to view hidden files and folders.  (You can turn that off afterward if you want, or leave it on.)
