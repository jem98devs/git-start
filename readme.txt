Welcome to My Project.

Author: Jem
firstname: Justine 
LastName = Mavunje 


Cheat Sheet - Git Commands Used in This Section
In this section, you created and worked with a local repository.

You used the following Git commands
Initialize an empty Git repository:

git init

Show the status of your repository:

git status

Stage a specific file:

git add readme.txt

Stage all changed files:

git add .

Commit the staged files:

git commit -m "Create readme file"

Define notepad as an editor. It will be used when you run the git commit command without -m parameter:

git config --global core.editor notepad

Show the changes of a specific file:

git diff readme.txt

Show the changes in your working directory:

git diff

Show the changes in your staging area:

git diff --staged

Show the history/log:

git log

Show the history/log with one commit per line:

git log --pretty=oneline

Checkout a specific commit by its snapshot hash:

git checkout b346471

Navigate back to your main branch:

git checkout main

Now you know how to work with a local repository.

In the next section, you will learn how to branch and merge your code. This can be helpful when you want to work on different features in parallel. But before that, let's test your knowledge with some learning questions.