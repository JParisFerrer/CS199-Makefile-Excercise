# CS199-Makefile-Excercise
SP17 CS199 Makefile Excercise

# Instructions
Hello everyone, in today's lecture we are going to be going over makefiles. The assignment is going to be distributed over github (here). Because it is a public repo, and we want you to work in private repos, you can't just fork it right away. So, this will be a several step process.

First, you need to have access to private repos. You can go here: https://education.github.com/pack to activate your student pack and get access to free private repos.

Next, clone the assignment:
```
git clone https://github.com/JParisFerrer/CS199-Makefile-Excercise.git
```
NOTE: If you don't have git installed, you are going to need to install it. If you're on windows, I recommend sshing into EWS to work on the assignment, others can either install it or ssh.

Now, you need to create a new repository. Login to github, and click the + next to your profile picture at the top right, and choose "Create repository". Make it private, name it something descriptive such as "My CS199 Makefile Excercise" (make sure it's different than the name of our repository), and make sure to check the box "Initialize this repository with a README", which will allow you to check it out immediately.

Once created, you will need to clone it. Go to the repository on Github, and click the green "clone or download" button on the right side. Copy the link there, and then in terminal again (not inside the folder you made before), run
```
git clone <your link here>
```

Now, copy all the files from our assignment repository into your private repository. Now run:
```
git add .
git commit -m "adding initial files"
git push
```
which will start tracking all the files, commit them, and then push that to Github.

At this point, you can start working on the assignment. When you have created your makefile and want to submit it, run
```
git add .
git commit -m "submitting makefile"
git push
```

# Grading

To grade your code, we need to be able to see your repository! So, you need to add us as Collaborators. To do so, open your github repository again and choose the Settings tab. Then you want to add **BOTH** Arman and myself. So you would add github users "JParisFerrer" and "armantajback" as collaborators.


If you have any questions, feel free to ask here or in class!
