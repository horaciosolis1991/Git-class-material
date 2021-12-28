# The remote repository

The local repository is pretty useful to keep a historical track of all your files, however, having you progress in a local repository does not allow you to leverage
one of the main features of Git: contribute with others.
The remote repository allow us to synchronize our local repository (and your local repository from your colleagues) with a repository located on the web ( on a server).



<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/Version-control-workflow.png" width="614" height="309">
</p>


## Creating a remote repository using BitBucket

1) Go to your BitBucket webpage and select "Repositories" tab in the left side of your screen, the following window will be seen:

<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/create-repo1.png" width="246" height="242">
</p>

2) Select create repository

<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/create-repo2.png" width="852" height="154">
</p>


3) Fill the information, according to your needs.


<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/create-repo3.png" width="502" height="448">
</p>


Now you have all to start working with your repo on the server, in brief we will check how to modify that repo locally ( on your computer).

## Cloning a remote repository

You can  clone a repository located on a server using your web interface in BitBucket or Github, however, this is not very practical because the destination path (to
download the file) will not be automatically initialized as a Git repository.
You can clone a repository and at the same time convert your destination folder in a git repo using the command **git clone "webadress/my-repo.git"**. Each time you 
clone a repository check that the origin url ends with a .git, trying to copy other paths such as "webadress/my-repo/browse" will produce an error and won't clone the
repository.




<p align="center">
<img src="https://github.com/horaciosolis1991/Git-class-material/blob/main/res/clone-bitbucket-repo.png" width="477" height="262">
</p>





**Notice that, by default, you will clone the main branch and the latest commit to that branch (HEAD).**


## Git pull


## Git push



## Pull request