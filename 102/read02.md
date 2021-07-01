# read 02

In today's lecture, we learned about the differences between Git & Github & also we learned the important aspects of how to implement the commands through CLI by using a program called Terminal.

We also learned about the differences between GUI & CLI which explain how the user is able to control & access certain options of the Operating System. The GUI stands for Graphical User Interface which means that the user has the ability to access files in a modernized design which is simple to use. On the other hand, CLI stands for Command Line Interface which means that the user can access files by using programs such as CMD or terminal which allows the user to insert command codes to simply add, modify or delete files in the Operating System.

The difference between Git & Github is the fact that Git is a control system that allows the user to manage his source codes in which they are installed & maintained on the local system.

 In addition, we learned how to connect our Github accounts with our Replit accounts so that we can clone our repositories & at the same time, we worked on how to implement the Git commands in the Replit which enables us to update our work (which is our previous files from previous lectures) which allows us to access our Github accounts in terms of updated markdown files.

 # Summary about Git Intro

 The terminal is a command language that used for MAC Operating system while the command line used for Windows Operating system. Depending on the version of the Operation system, programmers created the Local Version Control systems (VCS) which entails the database of the hard disk that stores changes for the files that are being operated.

 There's also version control systems such as Centralized Version Control System (CVCS) & Distributed Version Control System (DVCS). The difference between the 2 systems is the fact that the centralized system entails a single server for storing the data while the distributed system cannot collaborate the saved data because the main vulnerability of the centralized system is it cannot work on a saved file on a new version of the system.

 Git is a distributed system that stores data in a file which saves a changed version of the system which is also known as "commit". Git only relies on the local systems because it contains the necessary details in which user can get information from. When it comes to losing data, Git minimizes the the possibility of damaging the files which could be either destroyed or lost & it is a difficult situation for the Git because the committed data is lost.

 Git was released in 2005 in which developers stopped using distributed systems for such reason in which there was a tension between Linux & BitKeeper.

 Downloading the Git requires a computer that has the availability in which the user can download from or simply using it in the operating system depending on which the user is satisfied with. For Mac OS X, Git can be used in either Terminal, Git Website or GitHub. But for Windows, the user can use it in either  Git Website or GitHub & the same thing goes for Linux. However Linux requires to download the package manager in order to work with the Git language.

# Git coding examples

For coding purposes, we learned about how we can manage the Git using command line codes through the Replit & Terminal.

### Cloning

Cloning is based on copying a repository from the GitHub by using the command with a repository URL:

$ git clone https://github.com/test

### File handling

File handling is the most important factors in which the user must be able to access & control it. Here are the examples below:

git add filename

$ git add .

**In this code, git add means that it adds all files from the GitHub server into the Replit**

$ git commit -m "added new file"

**In this code, git commit means that the user staged multiple files which displays a message on what did the user do in the commit message**

$ git commit -a

**Just like the previous one, git commit a means that it saves all files**

$ git push origin main

**In this code, it states that it pushes the changes to a remote repository in which the command pushes the new changes to the original name which is "main"**
