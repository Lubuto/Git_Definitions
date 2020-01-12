GIT DEFINITIONS

1. Repository
A Git repository is the .git/ folder inside a project. This repository tracks all changes made to files in your project, building a history over time. Meaning, if you delete the .git/ folder, then you delete your project’s history

2. Branch
A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or master branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the master branch to publish your changes.

3. Commit
A commit, or "revision", is an individual change to a file (or set of files). It's like when you save a file, except with Git, every time you save it creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of what changes were made when and by who. Commits usually contain a commit message which is a brief description of what changes were made.

 4. Status
 A status is a type of status check on GitHub. See "Status checks."
 
 5. Stage
To stage a file is to prepare it for a commit. Because git exposes this action to the users control it allows you to create partial commits, or to modify a file, stage it, modify it again, and only commit or revert to the original modification.

6. Merge
Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another.
