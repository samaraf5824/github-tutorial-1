# GitHub Tutorial

_by Aaliyah Sealey_

---
## Git vs. GitHub
**Git** keeps track of your older code by taking snapshots.  

**Github** then takes that code and stores it in the clode which is also the internet.The difference between the two is github needs git but git doessn't need git.


---
## Initial Setup
* First go to [github](https://github.com/)
* Then click on the upper right corner where it says sign up **if you DONT have an account**
* After you want to create a username something easy to remember (or if you are apart of HSTAT use your email but take out @hstat.org)
* Then input your email adress
* Finally create a password and press the "sign up for github" button 
* After that you want to switch your account to SSH and to start go to the profile icon in the top rihgt corner
* on the left sidebar it will say SSH and GPG and click new SSH key and create a title "CLOUD9" [c9.io](https://c9.io/login) 
* then open up cloud9 and click you gear icon and copy and paste the second SSH key into github
  * starts with ssh-rsa
  * add SSH key
  * open the worskpace you are going to use for example mine is called (github-learning) and type ssh -T git@github.com
 * This will result in the workspace saying "Hi <your username>! You've successfully authenticated, but GitHub does not provide shell access."
 


---
## Repository Setup
1. _Git init_ = is used to initialize git in our repository once in the beginning. Make sure to cd into your repo and not to initilize in the workspace because it will create a hidden file. If you do use the comman rm -rf .git to delete the hidden file if you initiliza in the workspcae.  

2. After you _initilize_ your repo you want to add it to git by doing the comman git add . to add your current directory but not the ones that have been renmaed or moved. To add those files you want to do the command git add --all    
3. Then you want to commit a message by using commit -m "your message" that is heplful for you to look back on your code and find out what you did after you added and pushed your command to github.
4. The remote is when you are setting up a connection between your local remote (c9.io) and a regular remote github.


---
## Workflow & Commands



---
## Rolling Back Changes