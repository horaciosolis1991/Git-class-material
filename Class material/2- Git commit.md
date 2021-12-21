# Git commit

Git commit is one of the most useful and recurrent commands, it will save all changes done in the staging area.
Each time you use git commit is very important to add a brief message so you will know what the main changes were during that commit.


<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/git-commit-bad-practice.png" width="661" height="178">
</p>


Is very important to add a message to your commit, you can do that using git commit -m "my message", from the previous example, to create the commit #1 we
would use git commit -m "Fix 1". Notice that messages like "Fix 1" are a very bad practice, as they are not saying anything about what you did on your files.

A good practice is to add a brief but descriptive message to your commit as shown below:


<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/git-commit-good-practice.png" width="778" height="227">
</p>


## git checkout

The git checkout command is used to update the state of the repository to a specific point in the projects history. When passed with a branch name, 
it lets you switch between branches.Since this has the potential to overwrite local changes, Git forces you to commit or stash any changes in the 
working directory that will be lost during the checkout operation.

<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/before-checkout.png" width="540" height="231">
</p>


<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/after-checkout.png" width="540" height="280">
</p>




## git revert

Reverting undoes a commit by creating a new commit. This is a safe way to undo changes, as it has no chance of re-writing the commit history.





<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/before-revert.png" width="545" height="226">
</p>


<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/after-revert.png" width="751" height="276">
</p>



## git reset

On the commit-level, resetting is a way to move the tip of a branch to a different commit. This can be used to remove commits from the current branch.

<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/before-reset.png" width="545" height="226">
</p>

<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/after-reset.png" width="219" height="275">
</p>


In addition to moving the current branch, you can also get git reset to alter the staged snapshot and/or the working directory by passing it one of the following flags:


* soft – The staged snapshot and working directory are not altered in any way.
* mixed – The staged snapshot is updated to match the specified commit, but the working directory is not affected. This is the default option.
* hard – The staged snapshot and the working directory are both updated to match the specified commit.