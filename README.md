## Version Control 
As the name Version Control suggests, it is a system that records changes made to a file or a set of files. The system refers to the category of software tools that make it possible for the software team to look after the source code changes whenever needed. The system records all the made changes to a file so a specific version may be rolled if required in the future.

The responsibility of the Version control system is to keep all the team members on the same page. It makes sure that everyone on the team is working on the latest version of the file and, most importantly, makes sure that all these people can work simultaneously on the same project.

## Difference Between Git and Github
Git is a version control system that allows developers to track changes in their code. GitHub is a web-based hosting service for git repositories. In simple terms, you can use git without Github, but you cannot use GitHub without Git.

## 3 Other GitHub Alternatives
- GitLab
- BitBucket
- OneDev

## Difference Between Git Fetch and Git Pull
The key difference between git fetch and pull is that git pull copies changes from a remote repository directly into your working directory, while git fetch does not. The git fetch command only copies changes into your local Git repo. The git pull command does both.

## Git Rebase
Git Rebase is one of two Git utilities designed to integrate changes from one branch onto another. Rebasing is the process of combining or moving a sequence of commits on top of a new base commit. Git rebase is the linear process of merging.

A Git rebase changes the base of the developer’s branch from one commit to another, so it looks like they have created their branch from a different commit. Internally, Git creates a new commit and applies it to the specified base. However, it's essential for everyone involved to understand that although the branch appears the same, it's made up of entirely new commits. When you perform a Git rebase, you are, in effect, rewriting history.

#### Command for Git Rebase
```
git rebase main
```

## Git Cherry-Pick
Git Cherry-Pick is a powerful command that enables arbitrary Git commits to be picked by reference and appended to the current working HEAD. Cherry picking is the act of picking a commit from a branch and applying it to another. git cherry-pick can be useful for undoing changes. For example, say a commit is accidently made to the wrong branch. You can switch to the correct branch and cherry-pick the commit to where it should belong.

#### Command for Git Cherry-pick
```
git cherry-pick commit-ref
```
` 
Note: commit-ref is the commit reference. You can find a commit reference by using git log 
`
