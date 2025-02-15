# Prerequisites

Install Git graph extesion in VSC
![](media/git_graph_extension.png)

You can open the git graph view with next button
![](media/git_graph_button.png)

# GIT Tutorial

Here you can find the recomended steps to use Git andt Github using VSCode as interface.

Assuming that you already have a local git repository, follow the next steps:

1. `Update local repo`: Before start working on any change it is recommended sync your local repo with the remote repo. This way you can avoid merge conflicts. Remember you have to checkout manually to point at the last commit.
![](media/update_git_repo.gif)

2. `Commit changes`: Before commit any change, first you have to create a new branch, (Note: it is not recommended create commits in the main branch). Once the branch is created and you are pointing to it, you can now commit your changes. Take into consideration that before commit changes you have to added to "stage", changes not added to stage won't be commited.
![](media/commit_changes.gif)

3. `Push branch`: Now that you have the mew branch and the commit (or commits) in your local repo, next step is push your branch to the remote repo.
![](media/push_changes.gif)

# FAQ

Q:`I want to deliver changes but someone deliver his changes before. How can I deliver my changes without affect changes that are not mine?`
A: You have to merge your changes with the latest changes, sometimes it will be necessary to resolve merge conflicts(if both branches contains changes in same files and lines) if not merge conflict were found by git then merge will be done automatically and once it is completed you can push your changes, just make sure your commint doesn't contain any changes you didn't make.
![](media/merge.gif)
