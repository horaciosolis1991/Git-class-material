# Class 1 : Git introduction


## What is version/source control


Version control is a system that records changes made to a file or a set of files over time so that you can recall specific versions later. 
It is possible for the team to look after the source code changes whenever needed. 
The system records all the made changes to a file so a specific version may be rolled if required in the future.
The responsibility of the Version control system is to keep all the team members on the same page. It makes sure that everyone on the team is working on the latest version of the file and, most importantly, makes sure that all these people can work simultaneously on the same project.


![alt text](https://github.com/horaciosolis1991/Git-class-material/blob/main/res/Version-control-diagram.png?raw=true)





## Benefits of version control


![alt text](https://github.com/horaciosolis1991/Git-class-material/blob/main/res/Version-control-benefits.PNG?raw=true)



## Version control workflow

Pay attention now — here is the main thing to remember about Git if you want the rest of your learning process to go smoothly. Git has three main states that your files can reside in: modified, staged, and committed:

Modified means that you have changed the file but have not committed it to your database yet.

Staged means that you have marked a modified file in its current version to go into your next commit snapshot.

Committed means that the data is safely stored in your local database.

This leads us to the four main sections of a Git project: the working directory (or tree) the staging area, the Local repository (Git directory) and the remote repostory.


![alt text](https://github.com/horaciosolis1991/Git-class-material/blob/main/res/Version-control-workflow.jpg?raw=true)


### Working directory

Is a single checkout of one version of the project. These files are pulled out of the compressed database in the Git directory and placed on disk for you to use or modify.

### Staging area

The staging area is a file, generally contained in your Git directory, that stores information about what will go into your next commit. Its technical name in Git parlance is the “index”, but the phrase “staging area” works just as well.

### Local repository

The local repository is where Git stores the metadata and object database for your project. This is the most important part of Git, and it is what is copied when you clone a repository from another computer.


### Remote repository

Remote repositories are versions of your project that are hosted on the Internet or network somewhere. You can have several of them, each of which generally is either read-only or read/write for you.


The basic Git workflow goes something like this:

1) You modify files in your working tree.

2) You selectively stage just those changes you want to be part of your next commit, which adds only those changes to the staging area.

3) You do a commit, which takes the files as they are in the staging area and stores that snapshot permanently to your local repository.

4) If needed, you can pull those changes to your remote repository, so you can contribute with other team members.






