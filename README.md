# LEARNABLE GITHUB TASK

## Version Control
Version Control is a system that records changes made to a file(s). This system also serves as a platform where users can collaborate on projects. It helps the author of a file as well as collaborators to track modifications such as revertions, additions, who made a modification, and also comparison of changes done on the file overtime. Version Control Systems generally makes the process of developing a project seamless, since it tracks and records old and new modifications, thereby allowing mistakes to be undone. There are three types of Version Control Systems; Local Version Control Systems, Centralized Version Control Systems (Perforce, Subversion), and Distributed Version Control Systems (Git, Darc, Mecurial). Git is the most popular Version Control System in use.


## Difference Between Git and Github

Git is a popular free, open-source distributed version control system that tracks changes in any set of computer files, usually used for coordinating work among programmers who are collaboratively developing source code during software development while GitHub is a web-based hosting service for Git repositories. It makes Git more user-friendly and also provides a platform for developers to share code with others. It also has a robust API that allows developers to integrate GitHub into their own applications and workflows.

## 3 Github Alternatives
* SourceForge
* Bitbucket
* Gogs

## Difference Between Git Fetch and Git Pull

Git Fetch command is used to fetch all changes from the remote repository to the local repository. It doesn’t make any changes to the current working directory. It stores all the changes in a separate branch called the remote-tracking branch while Git Pull is used to fetch all changes from the remote repository to the current working directory. It automatically tries to merge or rebase them into the current working directory. It is the combination of git fetch and git merge or git rebase.


## Git Rebase and its Command
Git rebase is a command that allows for changes to be done on commits such as reordering, editing, combining multiple commits together, or deleting commits that are no longer needed.

#### The command for git rebase is:
``` git

git rebase --interactive OTHER-BRANCH-NAME

```

## Git Cherry-Pick and its Command
Git cherry-pick is a command that picks a commit from a branch and applying it to another commit. Cherry picking is an act of picking a commit from one branch to another. The git cherry-pick command is beneficial for making changes like switching a commit from a wrong branch to the right branch. 

#### The command for git cherry-pick is:

``` git
   git cherry-pick commit
```