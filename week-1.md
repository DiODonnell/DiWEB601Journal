# The First Week in WEB 601

![Web](web.jpg)
The first week has been busy. Our new tutor Ali Kahwaji 
arrived straight from a long flight from Barcelona and
he introduced himself and outlined his experience in 
the workplace as a full-stack developer. We are taking 
a project orientated stance for this course. This is
great for we will gain knowledge while learning how
a web app is developed in the workplace using an AGILE
approach - our iterations will be the three milestones
for our project.

We have begun learning how to use GitHub to control our
workspace and the development of our web app. We learnt some
basic commands and how we use them to control development
in such a way that each bug or change to our code is worked
in a sepearte area to the main project code that has been
checked and tested. In this way we can check our changes or
fixes before adding them to our main project code, it also
enables us to work on samll areas at a time - making our workflow
more manegable and keeping to the style of code that is not
the spagheeti type - that is it is clean and refactored and
modularised for reuse elsewhere.

The main project code is called the "Master" and sits in a 
repository on our remote server - Github. When we work on 
code we do so locally on our PC - this work is called our 
"working copy". This is held in a local repository - a root folder 
appended with .git, within our project folder, which holds the history
being a list of all our commits. 

It can be a bit confusing and I imagine for me just doing it and 
practicing will be key to getting familiar with the process and
the commands. This journal of my reflections on what I am learning
and doing on the WEB 601 course. We started learning the commands
using the interactive tutorial on learngitbranching.js.org. I prefer
learning by doing so it was really helpful - as well as saving me
from using my actual Github account to learn the basic commands.

I've started again from scratch to get the process from start to
finish memorised properly.
I started by creating a new folder locally for my course - it will 
hold everything I will be wanting to put in the remote server.

I am using Visual Studio Code for my editor and downloaded it and
set it up in the second class this week. I opened the new folder 
in VS Code and created this text file for my week one journal within it.

I now  open a terminal using Bash to enter my Git commands to
create my local repository.
Command: cd file path to folder
Then to make it a repository
Command: git init

I want to add my text file to the staging environment - which is 
where I add the latest changes to my file ready for a commit if I 
am happy with my changes.

Command: git add . or git add filename
Then I useCommand: git status
to check if that it has occurred

I then do a commit with a message that is meaningful
Command: git commit -m "Message"

I need to let the remote server know who I am for the push

Command: git config --global user.name "Me"
Command: git config --global user.email me@gmail
Command: git remote add origin https://github.com/DiODonnell/WorkSpace.git
Command: git push -u origin master
Each change after that I pushed using
Command: git push origin master

I then refreshed on GitHub and my text file is now there.
 Any changes I make locally I first stage add command and then commit with message and then 
 push to GitHub
 I made a branch locally called develop journal and switched to it with this code
 Command: git checkout -b developjournal

 It has been more complicated working with the remote repository than I thought
 it would be - yet so far I am able to pull and push from thereand have made a branch
 in the remote repository which has been checked as the master
 so I hope that when I push alterations it will go onto that
 branch until I check and merge it with the master on the
 remote repository. There is more to learn and I will continue
 to use the interactive learning platform as well as going
 through online tutorials in LinkedIn to get more adept at using Git.
 