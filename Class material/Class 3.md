# Git branches

In a nutshell, **branches are paralell lines of development for a certain project**.
A branch is created using the commad git checkout -v "branch_name", this command will quit the current branch to the new branch. The new
branch will contain the same information as the branch (HEAD) that you are using when calling the previous command.


<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/branches-intro.png" width="681" height="301">
</p>


Branches are very useful for several reasons:

* Create separate development paths without overwriting progress.
* Keep different lines of development isolated one from another, each branch may have a specific goal, for example.
* Very useful to contribute with others, as an user can own one or more branches.


<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/branches-utilities.png" width="573" height="283">
</p>


## Create new branch

As mentionned before, having multiple branches on a single projects is very useful, so, in order to create a new branch you can use **git checkout -b "branch_name"**,
this will leave the current branch and create a copy of it in the new branch.

<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/git-branch1.png" width="505" height="223">
</p>



Note: Be careful when creating a new branch, the content of that branch will be a copy of the content of the current branch ( and its commit) before the command execution.

<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/git-branch2.png" width="436" height="216">
</p>




## Switching branches

To switch  to a branch just use **git checkout"branch_name**. This command will leave the current branch (which could be anyone) and will switch to the specific
branch. Notice that checkout is used to change the branch but also the commit.
Also, you can see a quick summary about you number of branches using **git branch**.



<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/switch-branch.png" width="392" height="290">
</p>


## Deleting branches

Sometimes is a good practice to delete a branch after merging it with the main branch.
For cases like that you can delete your branch using  **git branch -d branch_name**  or **git branch -D branch_name** to forcely delete your branch.
Deleting a branch will also delete the information about all commits, be careful when deleting branches.



<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/git-delete-branch.png" width="375" height="211">
</p>



## Merging branches



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


## Solving branch conflicts

Merge conflicts are part of the git experience, most of the times git will handle properly to merge to branches, but there are some situations that are pretty hard
to avoid and may derive in merge conflicts such as :


* Two developers working on the same file and the same line.
* One contributor deleted a file, while other contributor was working on it.

Once a conflict ocurrs, the file in conflict ( in the branch that will receive the changes) will suffer some modifications, indicating that a conflict has ocurred.
The quickest and simplest way to solve a merge conflict is the following:

1) Once the conflict ocurrs, the file (s) in conflict ( in the branch receving the changes) will suffer some modifications, indicating the lines in conflict.
2) Open that file(s), and edit its content manually, it is very important to know beforehand what is the expected result of that change.
3) Once you end your modifications, move the file(s) to the staging area and commit them, Git will take that commit as the resolution of the conflict, even though the two
branches will still be different.

Merge conflicts are broader than the previous solution, for more information about merge conflict check the following links:

(add merge conflicts class link)
(add best practices link)




