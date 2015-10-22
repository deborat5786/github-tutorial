# GitHub Tutorial

_by Debora Tzunun_

---
## Git vs. GitHub
* __Git__ is a version control or a used to stage to save codes.
* __Github__ is a cloud where you store code.



---
## Initial Setup
1. In order to start git, you'll need to create a new [Github account](http://www.github.com). This website will be the clould where all your code gets push into 
2. After that, you'll need to create a SSH key. _this will store all the code into Github_ 
   * First, in order to do this you'll this need to click on your profile icon that is located on the right side hand corner of the website page of Github.com. 
   * When you clicked on your icon then, you should next click on the word "Settings"
   * Next, click on "SSH keys" on the left side menu.
   * After that, click on "Add SSH key". You'll see that you need a title for your key. Name it of the the website you be connect with github. Whether its [Nitrous](www.nitrous.io) or [Cloud9](www.c9.io) 
   * Finally, for this part you'll need copy and paste the key of the website to connect with github (to the website you be adding code). Click on "add key" and BOOM! SSH KEY IS CREATED
3. Now that you have your SSH key created, you now need to switch to your Nitrous or Cloud9 and begin to make a new directory. Lets type __*mkdir first-repo*__ to create you very first.
4. Go into first-repo, __*cd first-repo*__ click enter and type __*git init*__ , this will active git. 
5. Lastly, git config --global user.name "First Last" and git config --global user.email "Your Email"

You now completed the one-time setup of using github! 

---
## Repository Setup

Now that you're all setup, You're ready for add code



---
## Workflow & Commands
As you work through it is always important to check status, add, commit, and push 

1. First, check your status by typing __git status__
2. Then, add by typing __git add .__
3. Next, commit by typing __git commit -m "_file name_"__
4. Lastly we push by typing __git push -u origin master__

This should be the workflow that every user need to memorize in order to add, commit, and push 
 
 

