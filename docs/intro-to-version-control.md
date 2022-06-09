# Intro to Version Control

### Vocabulary
This is some vocab that will be helpful towards understanding.
> **Repository**: the data structure of your code, including a .git folder in the root directory

> **Commit**: a particular saved state of the repository, this includes all files and additions

> **Branch**: a means of separating various commits, having a unique history. This is primarily used for separating development and stable branches.

> **Push**: update the remote repository with your local changes

> **Pull**: update your local repository with the remote changes

> **Clone**: retrieving a local copy of a repository to modify

> **Fork**: duplicating a pre-existing repository to modify, and to compare against the original

> **Merge**: combining various changes from different branches/commits/forks into a single history


### What is "Version Control?"
Version control is how we as programmers are able to manage differing versions of code. This typically includes creating separate "branches" when implementing a group of functions. A good way to think about it is as a tree. (In fact, the term "working tree" is used to refer to files associated with an active project) Like a tree, projects usually consist of a **main** branch, or trunk, that contain a version that is shown to be fully functional. Other branches are used to individually work on different features and patch bugs in code.

The 342 programming team in particular works with forks. Each programmer working on the project creates their own separate copy of the main repository. As they make changes on their separate branches, they are able to test their own contributions and eventually merge with the main repository. Branches can be merged with the main repo when changes are tested and shown to be functional. 