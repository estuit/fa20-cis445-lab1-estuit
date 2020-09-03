[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=3064818&assignment_repo_type=AssignmentRepo)
# Lab 1: Git and GitHub

## Objective

Learn fundamental Git commands and GitHub access

## Instructions

* Install Git to your machine (download [Git](https://git-scm.com/))

* Read and follow the instructions in [First-Time Git Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup) to set up your Git environment

Note: It is important to follow the instructions to set up your identity and editor; otherwise, you'll encounter a famous/(my favorite <s>notorious</s>) editor, **vi/vim**, when you commit the changes to the repository. Once entering the vi/vim editor, you would not even know how to quit ^__^

* If you do not have a [GitHub](https://github.com) account using your **Bradley e-mail address**, create one

* Click the invitation link from Canvas (under **Assignments**) and accept the assignment

Note: Make sure that you are accepting the assignment with your Bradley e-mail instead of other accounts

Note: The first time you accept the assignment, you will see the whole class roster. Please select **your name**.
Once you accept the assignment, the repository of the assignment will be created, and you will see a page saying

    You are ready to go!
    Your assignment has been created here: https://github.com/CSIS-BU/[course]-[assignment]-[id]
    
    For example, https://github.com/CSIS-BU/cis445-lab1-djlin
    
* Click on the link generated the the step above, and you'll be landed in your lab repository In this page, you'll see two types of access to this repository

[SSH] git@github.com:CSIS-BU/cis445-lab1-djlin.git
[HTTPS] https://github.com/CSIS-BU/cis445-lab1-djlin.git

* Before you officially move on to the lab, learn what Git is through the following website

[Learn Git Basics](https://backlog.com/git-tutorial/what-is-git/)

I would recommend going through the whole Basics section. If your time allows, go on and read the **Learn Git Collaboration** section as well

* Through the guide, you should have learned how to create a repository through either the graphical user interface or command prompt. The following is for the instructions under command prompt

* Open a command prompt (**cmd** under Windows, terminal under other systems), change to a destination folder (where you will store your lab files), and execute the following (here we are access the repository through HTTPS)

    git clone https://github.com/CSIS-BU/cis445-lab1-djlin.git  <== Don't just copy-paste this line, you'll need to locate the URL of your own repository
    
* [optional] The other way to clone the repository is through SSH. For the sake of simplicity, we do not use SSH here as it would require you to set up the public/private keys. The command is pretty similar to the one above

    git clone git@github.com:CSIS-BU/cis445-lab1-djlin.git  <== Don't just copy-paste this line, you'll need to locate the URL of your own repository
    
* You may see a message "warning: You appear to have cloned an empty repository." if no documents are in the repository

* Now, your task in this lab is to create a file with the name [Your-First-Name].txt, and the content of the file should be a short paragraph introducing yourself. For example, what you like, don't like, favorite subjects, your plan after graduation, etc.

* After you're done editing the file, first commit your change(s) to your **local** repository

* [important] Then, make sure you **push** the local commit to the **remote** GitHub repositiory

* You can check if the commit is successfully pushed to GitHub by checking the repository in your GitHub page

* Note: You are encouraged to ask questions and help each other out for this lab. Use the **Discussions** function on Canvas
 
## Optional Exercises

Do the following exercises when you finish the lab requirements mentioned above

1. Monitor the _status_ of the repository when you do the following steps sequentially: (1) add a new file **bradley.txt** (2) stage the **bradley.txt** file (3) modify the **bradley.txt** file by adding your name. Note: check the status every time you finished a step
2. Delete the whole repository from your machine and use the git command to get it back from GitHub

## Rubric

* 1 pt: accept the assignment from GitHub 
* 1 pt: create a file with your name as the file name
* 1 pt: write an introduction to yourself
* 2 pts: successfully push the local repository to GitHub

## Helpful Resources

* [Pro Git (e-book)](https://git-scm.com/book/en/v2)

* [Git cheatsheet](https://github.github.com/training-kit/)

* [GitHub resources - Students](https://education.github.com/students)

* **Git/GitHub 101** Videos posted on Canvas
