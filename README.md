# ALP-Learning-01

ALP-Learning-01 is the first Repository for the Students of Android Labs. 

This repository is intended to get you all familiarized with the nuts and bolts behind the working of github and how to use this framework in building and contributing to Android Projects. 

So before we start using github I would like to answer two very important questions:
1. What is github?
2. Why github?

1. What is github?
GitHub is a Web-based Git repository hosting service. It offers all of the distributed revision control and source code management (SCM) functionality of Git as well as adding its own features.

2. Why github?
Github is a platform for hosting and collaborating on projects. You don't have to worry about losing data on your hard drive or managing a project across multiple computers - sync from anywhere. (You don't have to worry about the technical details, they will be explained in a short while). Github is a collaborative and asynchronous workflow for building software better, together. 
So "Building software better, together" would be the motto of Android Labs. 

Before a detailed summary of how to setup github on your local computers (I will tell you shortly why I mention local computers) is given, I would like to talk about (in simple terms) some of the so called "technical terms" I used in my explanation before. 

1. Organization - A group of people who contribute to a repository (just like a team in any other project). 
Some examples of organization are - PESU Sports Organization, PESU Android Labs Organization etc. 
An organization in github is nothing but a group of people who collaborate together to contribute to a "repository"
2. Repository - In simple vocabulary a repository is a location in which data is stored and managed. Github is not an exception. By repository we mean a central location for a project, where everyone contributes or collaborates. The project is hosted on github servers for which you may have a Admin(root level)/Member(Contributor/Viewer) Access. 
3. Admin - He is in charge of maintaining the repository. 
4. Member - A member is a collaborator or a viewer of a repository. Before making changes to the central repository (if he has write access), he has to take permission from the admin by "Opening a Pull Request" (explained below). 
5. Github distributed version control - Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. You would have noticed (especially those who have worked on Android Projecs b before), that a great going project gets "screwed up" in the end just because one of your devilish or unknowing teammates makes changes to a project and pressing our favourite Undo (Ctrl + Z) does not work in that case. The project may also get screwed up from the code written by you on a bad day. But with version control you can revert back to a previous state, revert the entire project back to a previous state, compare changes over time, see who last modified something that might be causing a problem, who introduced an issue and when, and more. Using a Version Control System (VCS in short) also generally means that if you screw things up or lose files, you can easily recover. If addition, you get all this for very little overhead. 

I hope by now you would have strong motivation about why using github is important for your projects. I will talk about how to setup github on your computer. 
I am covering steps on how to install github on Microsoft Windows Operating System (Windows 10/8/7 etc) and Linux Ubuntu Operating System. 

On Micorosft Windows OS:
1. Download git from http://git-scm.com/download/win. Your download starts automatically. Run the Git-***.exe file and follow the steps during the installation. 
2. If git gets successfully installed on your computer, you can type in the command git --version on the Windows Command Prompt. 
3. If it displays git version XXX. Then git has been successfully setup on your computer. 
4. Next step is to add your email id and name. Your email address should be same as the one used by you for signing up on github. E.g - my email id is "skymanaditya1@gmail.com" and github username is "skymanaditya1", if you are getting confused with my example consider your friend Rohin, his email address would be "rohinrohin@gmail.com" and his github username is "rohinrohin". 
5. If you have installed git successfully then you should be able to see git bash as a new software on your computer. You can do this step either using the Command Prompt (CMD for short) or git bash. I recommend using git bash.
Type in the following commands using any of the above (on the terminal):
git config --global user.name "Your name"
git config --global user.email "Your email"
e.g git config --global user.name "Syed Munawwar"
    git config --global user.email "syedmunawwar990@gmail.com"

6. After completing this step, you should be using git bash for setting up your projects on remote and local server. 
7. In simple terms, remote server is your project hosted on github and the local server hosts your project on your computer. 

On Unix Operating System (Ubuntu):
1. Open the terminal. 
2. Type in the command sudo apt-get install git
3. Configure the git settings as described before
4. git config --global user.name "Your name"
5. git config --global user.email "Your email"

Rest of the steps are going to be implemented in ALP-Learning-02
