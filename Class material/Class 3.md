# git branches

In a nutshell, **branches are paralell lines of development for a certain project**.
A branch is created using the commad git checkout -v "branch_name", this command will quit the current branch to the new branch. The new
branch will contain the same information as the branch (HEAD) that you are using when calling the previous command.


<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/branches-intro.png" width="851" height="377">
</p>


Branches are very useful for several reasons:

* Create separate development paths without overwriting progress.
* Keep different lines of development isolated one from another, each branch might be a specific goal, for example.
* Very useful to contribute with others, as an user can own one or more branches.


<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/branches-utilities.png" width="717" height="353">
</p>


## Create new branch

As mentionned before, having multiple branches on a single projects is very useful, so, in order to create a new branch you can use **git checkout -b "branch_name",
this will leave the current branch and create a copy of it in the new branch.

<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/git-branch1.png" width="851" height="377">
</p>



Note: Be careful when creating a new branch, the content of that branch will be a copy of the content of the current branch ( and its commit) before the command execution.

<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/git-branch2.png" width="851" height="377">
</p>




## switching branches

The switch branches just use **git branch "branch_name**. This command will leave the current branch (which could be anyone) and will switch to the specific
branch.





## deleting branches






## merging branches