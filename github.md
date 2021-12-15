# **github**
* Introduction
     - At a high level, GitHub is a website and cloud-based service that helps developers store and manage their code, as well as track and control changes to their code. 

* Git
     - Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
     - It is basically a content tracker
     

* Version Control System
     - Version Control System helps in handling this by maintaining a history of what changes have happened.
     - It just like undo cntrl+z

* Distributed Version Control System
     - Git is a Distributed Version Control System since the code is present in every developer’s computer. 
     - Like clone the whole project and push.

* Repository
     - It act as the main folder.
     - We can store our data as tree format.
* Clone
    - Download the whole project to our local system using SSH.
* Fork
      - To copy the whole repository on cloud and get sync with that main repository.

* Push 
      -  It is used to transfer or push the commit, which is made on a local branch in your computer to a remote repository like GitHub. 
* Pull
     -  The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. 
     - Merging remote upstream changes into your local repository is a common task in Git-based collaboration work flows. 
* Branching
      - Instead of copying files from directory to directory, Git stores a branch as a reference to a commit. Then merging the branch to master.
* Merging
      - merge our corrected file to main branch with comparison.**Merge conflict** also happened when both people give pull request then it will be resolved by own only.
* Revert 
       - To recover the pervious version from your histor
       - Note: It will delete all your new version after the revert file
* SSH - You can connect to GitHub using the Secure Shell Protocol (SSH), which provides a secure channel over an unsecured network.

**STEPS TO PUSH**
___________________________________
- Initialize - git init
- Stage - git add "file_name.html"
- Commit - git commit -m "message"
- Push - git push -u origin master
- Remote - git remote add origin "SSH"
- Branch - git checkout branch_name
      
 **(Also we have to access by Grapical User Interface)**
 - set token https://youtu.be/uFaYgSVzy3w
     - git remote set-url origin http://TOKEN_HTTPS
