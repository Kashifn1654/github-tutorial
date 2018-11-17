# GitHub Tutorial

_by Kashif Naseer_

---
## Git vs. GitHub
 **Git is an  version control system and GitHub is a web-page on which you can publish your Git repositories and collaborate with other people.**
 
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
 
Then go to c9.io and press the gear icon --> SSH keys tab --> copyand paste the SSH key in GitHub and add the SSH key.
    
---
## Repository Setup
* ```git init```: Then, initialize git in the new repository
* ```mkdir filename```: Create a folder or repository through the command line
* ```cd filename ``` :  Change into that folder
*  ```c9 README.md```: Open the README.md file and type something, and save the file.
* ```touch README.md```: Make a README file in the folder
* ```git status```: Type git status to check the changes made in the file.
* ```git add```: Type git add README.md to add the file to the stage
* git commit -m: Type git commit -m “” and add a message about the changes made.


---
## Workflow & Commands
* ```mkdir``` :creates a directory in the one thats working 
* ```cd``` : stands for change directory
* ```touch``` : craetes a new file 
* ```ls ```  :  list


---
## Rolling Back Changes
*  undo edits in order to undo a edit that you did in a file then do git checkout -- filename
* undo add in order to unstage a file you must git reset HEAD filename
* undo commits in order to undo a commit there are three possible ways of undoing
