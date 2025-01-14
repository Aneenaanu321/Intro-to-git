<---------------------------ABOUT GIT------------------------------>
Git is a version control system.

Git helps you keep track of code changes.

Git is used to collaborate on code.

Learning by Examples
In this tutorial, we will show you Git commands like this:

Example
git --version
git version 2.30.2.windows.1
For new users, using the terminal view can seem a bit complicated. Don't worry! We will keep it really simple, and learning this way gives you a good grasp of how Git works.

In the code above, you can see commands (input) and output.

Lines like this are commands we input:

Example
git --version
Lines like this are the output/response to our commands:

Example
git version 2.30.2.windows.1
In general, lines with $ in front of it is input. These are the commands you can copy and run in your terminal.

What is Git?
-------------
Git is a popular version control system. It was created by Linus Torvalds in 2005, and has been maintained by Junio Hamano since then.

It is used for:
---------------
Tracking code changes
Tracking who made changes
Coding collaboration
What does Git do?
-------------------
Manage projects with Repositories
Clone a project to work on a local copy
Control and track changes with Staging and Committing
Branch and Merge to allow for work on different parts and versions of a project
Pull the latest version of the project to a local copy
Push local updates to the main project
Working with Git
------------------
Initialize Git on a folder, making it a Repository
Git now creates a hidden folder to keep track of changes in that folder
When a file is changed, added or deleted, it is considered modified
You select the modified files you want to Stage
The Staged files are Committed, which prompts Git to store a permanent snapshot of the files
Git allows you to see the full history of every commit.
You can revert back to any previous commit.
Git does not store a separate copy of every file in every commit, but keeps track of changes made in each commit!
Change Platform:
Shift focus to GitHubGitHub
Shift focus to BitbucketBitbucket
Shift focus to GitLabGitLab
Why Git?
-----------
Over 70% of developers use Git!
Developers can work together from anywhere in the world.
Developers can see the full history of the project.
Developers can revert to earlier versions of a project.
What is GitHub?
---------------------
Git is not the same as GitHub.
GitHub makes tools that use Git.
GitHub is the largest host of source code in the world, and has been owned by Microsoft since 2018.
In this tutorial, we will focus on using Git with GitHub.
Git Install
--------------
You can download Git for free from the following website: https://www.git-scm.com/

Using Git with Command Line
To start using Git, we are first going to open up our Command shell.

For Windows, you can use Git bash, which comes included in Git for Windows. For Mac and Linux you can use the built-in terminal.

The first thing we need to do, is to check if Git is properly installed:

Example
---------
git --version
git version 2.30.2.windows.1
If Git is installed, it should show something like git version X.Y

Configure Git
----------------
Now let Git know who you are. This is important for version control systems, as each Git commit uses this information:

Example
git config --global user.name "w3schools-test"
git config --global user.email "test@w3schools.com"
Change the user name and e-mail address to your own. You will probably also want to use this when registering to GitHub later on.

Note: Use global to set the username and e-mail for every repository on your computer.

If you want to set the username/e-mail for just the current repo, you can remove global

Creating Git Folder
Now, let's create a new folder for our project:

Example
mkdir myproject
cd myproject
mkdir makes a new directory.

cd changes the current working directory.

Now that we are in the correct directory. We can start by initializing Git!

Note: If you already have a folder/directory you would like to use for Git:

Navigate to it in command line, or open it in your file explorer, right-click and select "Git Bash here"

Initialize Git
Once you have navigated to the correct folder, you can initialize Git on that folder:

Example
git init 
Initialized empty Git repository in /Users/user/myproject/.git/
