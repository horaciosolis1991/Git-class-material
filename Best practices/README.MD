# Why version control best practices are useful?


Version control isn’t just process for process sake. It ensures that the work you—and your team members—do is consistent, high-quality, and productive.

If you don’t follow version control best practices, you may frustrate your fellow developers and also make it:

Harder to roll back changes that break your builds,
More difficult you and team members to understand why changes were made in the first place, and
More likely that your code’s organizational integrity will suffer.

Now, lets check some of the most common and useful best practices.



## Write Good Commit Messages


Each commit should have a description that explains the why — but not necessarily the how — regarding the change. (How is usually deducible by comparing the file contents before and 
after the change.)
A good commit message makes it easier for a reviewer — and you — to understand the purpose of the commit later.  A good commit message also references the issue ID(s) — or even the 
requirement ID(s) — that the commit addressed (if applicable).	


## Commit Changes Atomically

One best practice is to commit changes atomically in version control.
All files in a commit are either committed together or not at all. No other user should see partial or incomplete changes.Commit all files that belong to a task in a single operation 
to keep the project consistent at all times.

## Do Reviews Before Committing to a Shared Repository

It’s also a best practice for version control to do reviews before committing to a shared repository.
A good commit is often reviewed before merging it to a shared repository. This is done either through a review system or a pull-request.
Reviews are a great way to get another perspective on a change and to improve code quality. Code reviews are also useful to increase code awareness within the team. This also enhances 
the team’s productivity through code reuse and higher quality of output.



## Follow Branching Best Practices

It’s also important in version control to follow branching best practices. So, what is the best practice for branching?
There are many.
Using branches is important for managing releases, new features and bugs. But there can be some challenges in branching. For instance, changes in one branch often have to flow to other 
branches. This makes it critical to follow branching best practices to avoid merge conflicts, lost updates, and unintentional overwriting of existing changes.

Branching best practices include:

-Try to keep things simple.
-Have well-defined code branching policies.
-Give codelines an owner.
-Uses branches for releases or milestones.
-Protect your mainline.
-Merge down and copy up.
