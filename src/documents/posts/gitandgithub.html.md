---
title: Git + GitHub
date:  Sat Feb 16 19:08:45 EST 2013
tags: ['git', 'github', 'how-to']
layout: post
---

There's a difference between Git and Github. Github is a place where you can host your repositories which in a non-techy vernacular means your code mush. 

There are other places to host your code mush, like Bitbucket and Gitorious but I use Github. The caveat with Github is your mush is in public, unless you pay for a private repo. So if you're just starting out, and you don't mind people seeing your mistakes, Github is a great place.

What do I mean by code mush?
---------------------------

You're baking a cake. You start putting ingredients in the bowl and then you stir them up and you pour them in a cake pan and you stick them in the oven and something goes wrong. And someone else comes into the room and they see that the cake didn't rise and they want to know why. Well if you're using git they will know why. If cake were like code, you could back up two steps or three steps, add a little bit of baking soda recompile and put the cake back in the oven.

That is Git.
------------

I have worked on dozens of codebases where multiple people attempt to bake a code cake simultaneously, without tracking what's going into the cake. 

When the cake didn't rise, everyone pointed a finger at everyone else. With Git, there's a feature built in called blame. If multiple people are working on a codebase at the same time, you can actually determine and point to who made the mistake, and when it happened. 

This actually lowers the stakes. Anything you can do with your code can be undone. 
