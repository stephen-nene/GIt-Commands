# GIT - GITHUB
Git and GitHub are two different things, but they are closely related.

Git is a version control system (VCS) that allows you to keep track of the changes made to your project over time. It enables you to save different versions of your code and easily switch between them, and also allows multiple people to work on the same codebase at the same time. With Git, you can keep track of the changes made to your project, revert to previous versions of your code, and collaborate with other developers.

GitHub, on the other hand, is a web-based platform that provides hosting for Git repositories. It allows you to store your Git repositories in the cloud, and also provides additional features such as a web-based user interface, issue tracking, pull requests, and wikis. With GitHub, you can share your code with others, collaborate on open-source projects, and easily manage your codebase.

In summary, Git is a tool that you install on your computer, whereas GitHub is an online service that you can use to store and share your Git repositories. You can use Git on its own, but GitHub provides additional features that make it easier to collaborate and share your code with others.
# GIt-Commands
Here are some common Git and GitHub commands that you may find useful:


```git clone [repository url]:``` This command is used to copy a remote repository to your local machine.

```git pull:``` This command is used to retrieve and merge the latest changes from the remote repository to your local repository.

```git push:``` This command is used to upload your local changes to the remote repository.

```git branch:``` This command is used to list all of the branches in your local repository.

``git branch [branch name]:`` This command is used to create a new branch.

```git checkout [branch name]:``` This command is used to switch to a different branch.

```git merge [branch name]:``` This command is used to merge changes from one branch into another.

```git add [file name]:``` This command is used to stage changes for commit.

```git commit -m "[commit message]":``` This command is used to save changes to the repository with a message.

```git status:``` This command is used to check the current status of the repository, including which files have been modified and which changes have been staged for commit.

```git log:``` This command is used to view the commit history of the repository.

``git remote -v :`` This command is used to see the remotes associated with the repository

```git remote add [name] [url] :``` This command is used to add a new remote repository

```git fetch [remote name] :``` This command is used to download objects and refs from another repository.

```git init:``` This command is used to initialize an empty Git repository on your local machine. It creates a new subdirectory called .git that contains all of the necessary files for the repository.

``git remote add [remote name] [remote url]:`` This command is used to add a new remote repository to your local repository. The "remote name" is typically "origin" and the "remote url" is the web address of the repository on GitHub.

`git config --global user.name "[your name]" and git config --global user.email "[your email]" :` These commands are used to configure your username and email address for Git. This information will be included in the commit history, allowing others to see who made the changes.

`git diff:` This command is used to view the differences between the files in your working directory and the files in the repository. It will show you the changes that you have made but haven't yet committed.

`git stash:` This command is used to temporarily save changes that you have made but haven't yet committed. This is useful when you need to switch branches or pull in updates from the remote repository without losing your local changes.

`git stash apply :` This command is used to apply the most recent stash to your current working directory

`git stash pop :` This command is used to apply the most recent stash and remove it from stash list

`git stash list:` This command is used to list all the stashes that have been created

`git stash drop [stash_name]:` This command is used to remove a stash from the stash list

`git tag [tagname]:` This command is used to add a tag to the current commit. Tags are used to mark specific points in the commit history and can be used to mark releases of your project.

`git tag -d [tagname]:` This command is used to delete a tag from the repository

`git fetch --all:` This command is used to download all branches from all remotes.

`git fetch [remote name] [branch name]:` This command is used to download a specific branch from a specific remote.

`git push --force:` This command is used to force push changes to a remote repository. This should be used with caution, as it can overwrite other people's changes.

`git reset [file name]:` This command is used to reset a file to the version in the last commit.

`git clean -f :` This command is used to remove untracked files from the working directory

`git clean -fd :` This command is used to remove untracked files and directories from the working directory