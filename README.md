61ABC Hackathon 
=========

The 61ABC Summer 14 Hackathon Hosted by: Hackers@Berkley, CSUA for students of the Summer 61 Series

Time: 6/18/2014. NOW - Midnight. 

Submit
-----------------
URL: https://docs.google.com/forms/d/1Yz2bcvZXowxVc34XuSvithKL-eWbgqlg4zYLjW7_jLM/viewform?usp=send_form


What is a hackathon?
------------------
A hackathon is usually an event (usually around 12 to 48 hours longs) where you (and your team) set to build something cool - with either hardware or software. At the end, you present what you built. There is no project spec - you just build something useful & cool! 

Groups & Mentors
------------------
Yes! If you work in a group - you will get a mentor who will help guide you in the right direction!
Come to the front if you don't have a group. 

Schedule 
------------------
- 5:00 - 5:30: Intro + Teamforming + Mentoring + Ideas 
- 5:30 - 6:00: Git Intro + Quick overview of what’s in the material 
- 6:15 - 11:30: 
  -  1. Use self paced workshops
  -  2. Talk to your mentor
  -  3. Hack away and build your idea! 
- 11:30 Submission Deadline. 
- 11:30 - 12:00 Judging. 

Setup
------------------
In order to get started quickly, we ask that you have these tools installed:
- Some sort of code editor (Sublime Text: http://www.sublimetext.com/3) 
- Git: http://git-scm.com/download
- Git GUIs: http://git-scm.com/download/gui
- Github account: https://github.com/
- Python3: https://www.python.org/downloads/
- Google Chrome (it HAS to be Chrome): https://www.google.com/chrome/browser/

=========

INSTALL THIS FIRST: http://git-scm.com/download

If you're using windows - use Git Bash! 

Getting this repo
-----------------
Go into a folder and run this command. 

`git clone https://github.com/42cs/hackathon.git`

Now, see what files are here. We'll have a hackathon folder. 

`cd hackathon`

-----

Creating a repo
-------------------
Now let's start our hackathon code. 
Go into a folder you'd like to 

`mkdir myhackproj`

Now we'll start the git project. 

`git init`

This starts a git project in our folder. 

Let's start our hack
-------

Let's create a file. hack.py 

Tell git to add it. 

`git add hack.py`

Commit & Saving
--------
Commits = = Saving in Git. 
`git status`
`git commit -m 'First Commit'` 
`git log`



Setting up a git repo on github. 
---------

- All you need to do is after you are signed up to github, go to homepage and you'll see a green button that says "new repository", click that button.
- Name the repository accordingly with your project.(A word of advice, choose a simple name)
- Then click create repository.
- Voila, now you have a github repository in your account, this will be the environment you will keep all your project files.
- Now you should add collborators. 

Push
-----
` git push origin master` 

Pull. 
-----

` git pull origin master`


Continuing
===========
http://42cs.github.io/book/week3/git.html

=========
Workshops
=========

0. Git Workshop.  In this repo. 

1. Building a Web Application with Python (Flask) - Link: https://github.com/daylen/cheeper
  - What the final product is - http://cheeper-demo.herokuapp.com

2. HTML Workshop - Room Here: https://github.com/webdesigndecal/cs-workshop/tree/master/su14

3. Mentoring - Throughout the worksho. 



Helpful content
================

- Sumukh's Hackathon Tips: https://github.com/Sumukh/HackathonWorkshop
- Guide to Git: http://42cs.github.io/book/

Ideas
===========
Flask chatroom: make a chatroom with flask: medium
DanRank: Reddit/HackerNews, for pictures of Dan Garcia (or anything else, but preferrably Dan Garcia): easy
TextAdventures.py: python textadventures game: easy
TextAdventuresOnline.py: Online multiplayer python textadventures game: hard
Game of life
Wa-tor

Ideas from CS42 Week 5 that can work with Flask + HTML:
 
RandomExamPractice - Get a random practice problem or midterm every time you load the exam. (Can make it real time really quickly with a quick script) 

RandomGifChooser - Loads a random GIF in full screen (with submission) - Based off the Flask Starter Project

YoutubeSubmission - Submit related youtube videos and watch them with this interface. 
ShareYoutube - Realtime requires some JS knowledge but not much. 

StudyTIME - Flask Web App to schedule a time to study/meetup for a specific topic/class
(side note: like pandascheduler but simpler) 

TrackChanges - Updates you when a website changes. (Think telebears or cs61 project releases) 

Something Fun with Twilio (An API to send SMS/make calls) 

FreeFoooooood - Tracks what events have free food on campus. 

- A compiler that turns an outline into an essay
- A Chrome plugin that turns all of my currently open tabs into a Works Cited page
