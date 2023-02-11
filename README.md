# GitCommands

Git is a powerful version control system that has become an essential tool for developers everywhere. Whether you're working on a personal project or collaborating with a team, Git provides you with the ability to manage your code, track changes, and ensure that everyone is working with the latest version of your codebase. In this blog, we'll be discussing the top Git commands that every developer should know. These commands will help you to streamline your workflow, work more efficiently, and take your coding game to the next level. So, let's dive into the world of Git!

1. git init

This is your first step into the world of Git.This command is used to initialize a new git repository in the current working directory.It creates a hidden git directory to help you get started with your project.

2. git clone

You use git clone when you need to create a local copy of a git repository from a remote repository.The code is automatically downloaded into your machine and you can view it in the directory.

3. git branch

Suppose you are working as a developer and you want to create a new feature in your project without disturbing your teammates, for that you would use the git branch which would create a copy of the repository in which you can work in without affecting the other members of your team.

4. git checkout 

This command is similar to the branch with the distinction being that you can use it to switch to an existing branch or you can just create and switch at the same time using the checkout command.You can also use this command to checkout the different files between the branches.

5. git add

This command allows you to add your files to the staging area where you can compare your local version of the file with the ones in the local repository for any conflicts you might need to resolve before pushing it.

6. git commit

The commit commands saves all of your made changes to your local repository.Point to note here that till this step the files have only been changed at the local level.The remote repository has not been changed yet.Another important feature is to add a commit message with the changes you are making so that your fellow developers know the summary  of the changes you have made.


7. git push

The push command allows you to push your local changes into the remote repository.All of the changes will now be present in the remote repository.Usually while pushing you may get some merge or conflict errors which you need to resolve in your repository locally before they can be pushed to the remote repository.


8. git pull

We have talked about cloning a repo and pushing your changes to the remote repository.But what if a fellow developer wants to obtain your code.For that you would use the git pull.It brings all of the changes made in the remote repository to your local repository.

9. git merge

You use this command when you want to merge a child branch with a parent branch.This command runs when there are no conflicts between the two branches otherwise you have to first resolve those errors before moving on.


10. git status

It gives you information about the current status of you local repository.Changes that have been stashed,changes that have not been staged,untracked files,number of commits behind the parent branch etc.


11. git revert

Suppose you have made a mistake and now you want to goto a previous version of your project.Each time you committed ,Git keeps record of all the changes that you have made.Git calls this version control,giving you the ability to go back to any previous version of your projects.
