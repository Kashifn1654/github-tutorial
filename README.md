# GitHub Tutorial

_by Kashif Naseer_

---
## Git vs. GitHub
 **Git is a version control system and GitHub is a web-page on which you can publish your Git repositories and collaborate with other people.**
 
* Git
    * snapshot 
    * DOES NOT REQUIRE GITHUB
* Github
    * requires git
    * store code in the cloud
    * track changes
    * collaborate files

---
## Initial Setup
##### Making a Github 
* go to  [Github](https://github.com)
        *click sign up
    * put all neeeded information
#####  SSH Key stands for secure shell and establishs a secure connection between your computer and GitHub

Go to GitHub, and go to your profile settings.  
Next, click on SSH and GPG Keys.  
Then, click on New SSH key to make a new SSH key.  
Then go to c9.io and press the gear icon > SSH keys tab > copy from cloud9 and paste the SSH key in GitHub and add the SSH key.  

---
## Repository Setup
* ```git init```: Then, initialize git in the new repository
* ```mkdir filename```: Create a folder or repository through the command line
* ```cd filename ``` :  Change into that folder
*  ```c9 README.md```: Open the README.md file and type something, and save the file.
* ```touch README.md```: Make a README file in the folder
* ```git status```: Type git status to check the changes made in the file.
* ```git add```: Type git add README.md to add the file to the stage
* `git commit -m`: Type git commit -m “” and add a message about the changes made.


---
## Workflow & Commands
* ```mkdir``` :creates a directory in the one thats working 
* ```cd``` : stands for change directory
* ```touch``` : craetes a new file 
* ```ls ```  : Lists all the files and folders in the directory you are in.  



---
## Rolling Back Changes
* undo push: ```git reset --hard HEAD~1``` leads you to your edits
* undo add: Once you add you can reverse it by ```git reset HEAD flename```
* undo commit:```git reset --soft Head~1```
* undo edits: ```git checkout --filename```
## How to Handle Errors?
* If you used git init into your workpace you should see 
   ```~/workspace (master)``` 

* Then all you have to do is ```rm-rf .git``` now you know how to get back


## Git clone, Forking,Pull
* Git clone is when you get a local copy of your repo
* Git Pull updates the local changes to the remote
* Forking is a copy of the repo allowing you to experiment openly without any worries of changing the original content
