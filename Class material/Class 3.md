# git branches

In a nutshell, **branches are paralell lines of development for a certain project**.
A branch is created using the commad git checkout -v "branch_name", this command will quit the current branch to the new branch. The new
branch will contain the same information as the branch (HEAD) that you are using when calling the previous command.


<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/branches-intro.png" width="681" height="301">
</p>


Branches are very useful for several reasons:

* Create separate development paths without overwriting progress.
* Keep different lines of development isolated one from another, each branch might be a specific goal, for example.
* Very useful to contribute with others, as an user can own one or more branches.


<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/branches-utilities.png" width="573" height="283">
</p>


## Create new branch

As mentionned before, having multiple branches on a single projects is very useful, so, in order to create a new branch you can use **git checkout -b "branch_name",
this will leave the current branch and create a copy of it in the new branch.

<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/git-branch1.png" width="505" height="223">
</p>



Note: Be careful when creating a new branch, the content of that branch will be a copy of the content of the current branch ( and its commit) before the command execution.

<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/git-branch2.png" width="436" height="216">
</p>




## switching branches

The switch branches just use **git checkout"branch_name**. This command will leave the current branch (which could be anyone) and will switch to the specific
branch. Notice that checkout is used to change the branch but also the commit.
Also, you can see a quick summary about you number of branches using **git branch**.



<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/switch-branch.png" width="392" height="290">
</p>


## deleting branches

Sometimes is a good practice to delete a branch after merging it with the main branch.
For cases like that you can delete your branch using  **git branch -d branch_name**  or **git branch -D branch_name** to forcely delete your branch.
Deleting a branch will also delete the information about all commits, be careful when deleting branches.



<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/git-delete-branch.png" width="375" height="211">
</p>



## merging branches



Merge enables you to combined two branches, integrating them in one single branch.
Let's assume that we have a second branch based on the main branch, we have develop some functionalities on that new branch and we want to integrate them
with our main branch.


<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/before-merge.png" width="384" height="168">
</p>


To merge the two branches we use the command **git merge "branch_to_merge"**. We select the branch we want to merge so it is very important to know on which 
branch we currently are, as that branch is the one that will get the merge content. Git will determine an algorithm for the merge.
After appliying the merge this is the scenario:

<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/after-merge.png" width="462" height="197">
</p>






