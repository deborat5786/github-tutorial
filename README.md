# GitHub Tutorial

_by Debora Tzunun_

---
## Git vs. GitHub
* __Git__ is a version control or is where you manage or command codes into another local system.
* __Github__ is a cloud where you store code. Is where you put your command of codes into.
* Git and GitHub are commonly alike from each other because both have to do with coding and connects with each other. Contrastly, git is what code takes place and github is what code is store in 



---
## Initial Setup
1. In order to start git, you'll need to create a new [Github account](http://www.github.com). This website will be the cloud where all your code gets push into 
2. **SSH Key:** After that, you'll need to create a SSH key. _this will store all the code into Github_ 
   * First, in order to do this you'll  tneed to click on your profile icon that is located on the right side hand corner of the website page of Github.com. 
   * When you clicked on your icon then, you should next click on the word "Settings"
   * Next, click on "SSH keys" on the left side menu.
   * After that, click on "Add SSH key". You'll see that you need a title for your key. Name it of the the website you be connect with github. Whether its [Nitrous](www.nitrous.io) or [Cloud9](www.c9.io) 
   * Finally, for this part you'll need copy and paste the key of the website to connect with github (to the website you be adding code). Click on "add key" and BOOM! SSH KEY IS CREATED
3. Now that you have your SSH key created, you now need to switch to your Nitrous or Cloud9 and begin to make a new directory. Lets type __*mkdir first-repo*__ to create you very first.
4. Go into first-repo, __*cd first-repo*__ click enter and type __*git init*__ , this will active git. 
5. Lastly, git config --global user.name "First Last" and git config --global user.email "Your Email"

You just now completed the one-time setup of using github! 

---
## Repository Setup

Now that you're all setup, You're ready to code!

1. First of all, of course you will need to initialize git. BUT! first go to the file where you gonna start git. This is important because you may initialize git in the file you DON'T need to. In order to do this you need to make a new file by typing out __*touch README.md*__ .
2. Before adding anything into this file, we need a new repository. So back to your git you need to click on the "+" sign on the top right corner of the github website. click on "new repository" . 
3. Next, its asking for a repository name. THIS SHOULD MATCH THE NAME OF YOUR FILE FROM YOUR GIT! which in this case id "first-repo"
4. Finally, you click "Create Repository" and FINISH! now you are ready to add and commit changes! 




---
## Workflow & Commands
As you work through it is always important to check status, add, commit, and push 

1. First, check your status by typing __git status__
2. Then, add by typing __git add .__
3. Next, commit by typing __git commit -m "_file name_"__
4. Lastly we push by typing __git push -u origin master__

This should be the workflow that every user need to memorize in order to add, commit, and push 

##Collaboration (Extra Credit)
* **Forking** is when you take another remote repository to your remote to enter in into your local machine by cloning. 

* **Steps on Forking Someone's Repository**
 1. In Github, choose someone repo you would like to fork. You should see in the upper top corner, underneath your profile icon, the work "Fork". click on it!
 2. Then, you should copy the SSH clone url and paste it to your local machine ( Nitrous or Cloud9) after your type *__git clone ( _url_ )__*
 3. Finally, your pretty much done, you now got the person's repository copy
 
 

