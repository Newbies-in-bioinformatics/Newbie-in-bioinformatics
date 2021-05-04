---
layout: post
title: Getting started with Git and GitHub for bioinformatics newbies (or any open scientist!)
subtitle: By Yo Yehudi
thumbnail-img: assets/img/YO_YEHUDI.jpg
---


>Yo Yehudi is an Open Source Technical Lead in the Data for Science and Health priority area at the Wellcome Trust and also the co-founder of Open Life Science, which is an amazing organization promoting open science. Apart from it, she is an open science evangelist and an incredible mentor who has mentored and educated many learners through training workshops, programs like [Google Summer of Code](https://summerofcode.withgoogle.com/), [Outreachy](https://www.outreachy.org/), [Open Life Science](https://openlifesci.org/), [Hacktoberfest](https://hacktoberfest.digitalocean.com/), and many conferences like [BOSC](https://www.open-bio.org/events/bosc/), [MozFest 2018 Openness space wrangler](https://www.mozillafestival.org/), and many more.

She was extremely kind to write a blog on getting started with GitHub for newbies. 


Learning to use Git can be intimidating at first, but once you've learned to get comfortable with it, you'll wonder how you ever did without it. 

GitHub is an online hosting platform for Git version control which is quite popular, but most of these points apply to any online Git hosting service, such as [GitLab](https://about.gitlab.com/) or [BitBucket](https://bitbucket.org/). 

Each of these  sections can be useful on their own, but over overall I'd recommend learning a little bit about  git and how it works, spend some time working on test repos of your own, then perhaps spending some time contributing to others' repos. Once you're comfortable with all those, running your own project collaboratively on GitHub will come naturally. 

## Why Git? 

- **Never lose work again**. No more `Copy 1_final(with revisions)USE_THIS.txt` filenames needed once you learn how to use version control. If you commit your work regularly, you can go back to any point in time easily, to when things last worked. 
- **Collaborative working** distributed version control like Git makes it easy to merge changes from multiple contributors, and GitHub has additional project management and issue management layers that help in tracking bugs, fixes, and planned features.
- **Free backups** - push your work from your computer to GitHub and no need to worry if your computer is stolen or your hard disk fails. 

## Awesome - how do I start? 
There are lots of different lessons online - you could try any of these self-taught/self paced resources:  

- Open Life Science's [GitHub lesson on YouTube](https://www.youtube.com/watch?v=Hj4kpy9LB6c)
- The Turing Way's [Guide to Collaboration](https://the-turing-way.netlify.app/collaboration/collaboration.html)
- Self-paced lessons on [Open Scientific Code using Git and GitHub](https://open-source-for-researchers.github.io/open-source-workshop/) that can also be used to deliver a class, using GitHub desktop. 
- The Carpentries: [Version control with Git](https://swcarpentry.github.io/git-novice/), using the command line 

If you keep an eye out, many of these organisations  may also run tutorials online that you can sign up to for realtime teaching. 

## Terminology

Here's a quick glossary for some terms you may encounter whilst reading these lessons: 

- **Commit** - a single git "save" point, usually with a message about what's just been saved, e.g. "Fixed a typo" or "the header is red now not blue".
- **Repository** the place where you store your code. a repository is made out of code and usually has multiple commits (possibly hundreds or thousands over time). 
- **Branch** - branches are optional, but they can be useful to make separate spaces for people to work on differnet things - so you might make a new "branch" to add a new feature to your code, allowing you to make commit saves without messing up the main branch. 
- **Merge** - when you have work from multiple people or multiple branches and you wish to combine them, this is known as a merge. 
- **Pull request** -  a request from an external contributor to merge work. They're requesting that you pull their work into your repository. 

## Contributing to someone else's repository

If you're interested in contributing to someone else's repo, you have a few options. It's usually easier to contribute to some repos and harder to contribute to others, depending on if they've designed their repo for contributions. 

- **contributing.md** - if you're really lucky, there's already a guide - often named contributing.md - in the repo in question that will tell you how to get started. [Here's an example from Emma Karoune](https://github.com/EKaroune/Open-Science-in-Phytolith-Research/blob/master/contributing.md). Projects with contributing guides are expressly thinking about how to bring in new contributors so they're your best bet. 
- **Check the project issues and project boards** - the issues tab may have features or bugs that need to be worked on. Look especially for labels like "good first bug" or "first timers". If the detail on the issues isn't sufficient to understand what to do, take a look around and see if there are any docs that might tell you how to get started. Sometimes issues aren't well defined enough to be useful to a newbie - don't feel bad if this is the case, it's definitely not your fault. In fact, I've closed issues that _I've written myself_ saying "I clearly knew what I intended when I wrote this issue but have no idea what it means now." :laughing: 
- **Email / chat message the maintainers** - if the above two fail, you might still be able to help out if you contact the maintainers and offer your services. Few people turn down offers of help! 
- **Still stuck?** Sometimes people put their code online but are no longer able to maintain it, or don't have the time or inclination to curate and review new contributions. This happens all the time and will probably happen to you too if  you end up using GitHub a lot! Don't feel bad if you can't figure out how to contribute, just move on to another repo, or make your own. 

## Working on your own

A few more tips for getting started on your own project. Remember that anything in your brain will get forgotten, so write clear readmes, clear contribution guides, etc. Also make sure to add a [licence](https://choosealicense.com/) so people are legally  allowed to re-use your work - otherwise all the code that's online can be looked at but is illegal to re-use. Take a look at [opensource.guide](https://opensource.guide/) for more tips and good practices.

At this point you may want to reflect a little on what you've learned from looking at and contributing to other people's repos - when you make projects that are online, open, and designed for contribution, it helps to create guides so that others know how to contribute and what culture your project has, what plans, etc. Every time you think "argghhh, I can't figure out how to do this" - make a note and make sure you make it easier to manage in your repo with clearer docs - or when someone asks for help whilst contributing to your work, treat them with a little sympathy as you'll remember what it was like when you were learning!
