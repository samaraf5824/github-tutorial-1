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
1.``` Git init``` = is used to initialize git in our repository once in the beginning. Make sure to cd into your repo and not to initilize in the workspace because it will create a hidden file. If you do use the command ```rm -rf .git``` to delete the hidden file if you initilized in the workspcae.  

2. After you _initilize_ your repo you want to add it to git by doing the comman git add . to add your current directory but not the ones that have been renmaed or moved. To add those files you want to do the command git add --all    
3. Then you want to commit a message by using ```commit -m "your message"``` that is heplful for you to look back on your code and find out what you did after you added and pushed your command to github.
4. The remote is when you are setting up a connection between your local remote (c9.io) and a regular remote github.
5. To create a new repo on github you want to sign into your account then plus the plus sign on the upper right corner and click new repository
6. You then want to name it the same thing as the title for the repo on your cloud9 file 


---
## Workflow & Commands
1. ```git status``` = this command is used to check the status of your working directory to make sure that all your files have been staged and pushed to github 
   * if the file is in red your file hasn't been staged / pushed to git but if it's green or says working directory clean nothing to push then eveyrhting has been saved and commited 
2.  As said before when you add you are putting something on the stage and when you commit a message your writing a message on what action you just took o what type of edits or code you wrote
3.  Finally after you've added and commited your message you do git push 
4.  ```Git push``` is what you use to push your code to github to be saved or for it to be taken a "picture" of but once in the beginning you want to do ```git push -u origin matser``` so it knows where to push to and then you can type in git push the other times


---
## Rolling Back Changes
1. undo add = to undo what you just put on the stage in git you use the command ```git reset filename.txt``` which will unstage your file 
2. undo commit = to undo a commit you want to use ```git reset --soft HEAD~1 ``` which is different from ``` git reset --hard HEAD ~1 ``` because the second one will permanently lose your changes while the first one I mentioned wont cause you to lose all of your changes.  
3. undo push =
4. undo edit 
5. 


---
## Extra Information That's Helpful To Know
1. fork and ```git clone``` 