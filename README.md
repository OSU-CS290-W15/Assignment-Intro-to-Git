Assignment-Intro-to-Git
=======================

The basics of Git usage

## Overview

In this assignment you will demonstrate your ability to use basic Git functionality to clone this repository, make changes to a file on the master branch, make a feature branch, merge the feature branch, roll back a commit.

## Instructions

1. Create a new repository called `assignment1`
2. _Add_ a file called bio.md. This should be a simple, plain text document. If you want to add [fancy formatting](https://help.github.com/articles/markdown-basics) you are welcome to do so. A .md file can have just plain text or you can add some simple formatting to get it to display well in a site like GitHub. Leave the file empty for this step.
3. _Commit_ this to your repository.
4. Add some basic info to your bio.md file. Things like hobbies and interests that you want to share.
5. Add a header (this can just be text that says 'Programming Background' on a single line) for a section on _programming background_ (but don't add content).
5. _Commit_ those changes.
6. Make a branch called _programming-bio_.
7. Make at least two commits in this branch adding information about your programming background in the _programming background_ section. This can be things like your favorite project in 161/162 or any other programming work you have done.
8. Switch back to your _master_ branch. 
9. Add more info to your bio non-programming bio and _commit_ that change.
10. Merge the _programming-bio_ branch with your _master_ branch.
11. Add some more content.
12. _Commit_ that content.
13. Make a _branch_ off the 2nd to last commit called _alternate-bio_. Make a change there and commit it.
14. Push all of this to a Git repo the instructor can assess. (Probably your student GitHub repo)

## Final Product

You should have a commit history with the following content:

- Two commits
- A branch off of the 2nd (or later) commit called _programming-bio_
  - This branch should have at least 2 commits
- At least one commit after this in _master_
- A commit merging _master_ and _programming-bio_
- At least one commit following that merge
- A branch created after (in terms of date and time) the last commit on master that points to the 2nd to last commit on the master branch. This branch should have 1 commit and be called _alternate-bio_.

The following is the output of `git log --graph --all --decorate

[Result of Commits](http://i.imgur.com/BmRMOVt.png)

## Grading

The grading will be based on the extent to which the above instructions are followed. If you deviate from the instructions, you will potentially lose points. Even if you think you are 'improving' something.

### Suggestions of Additional Exercises

The following are things which you are likley to encounter on an exam or in practical use of Git:

- Learn how to rebase
- Work with another student and see how two people working on the same project works
- Get yourself into a situation where there is a merge conflict and resolve it
- Work with another student, push a branch to a repo, have them pull that branch make commits and merge. Then rebase that branch and have them pull it again. The results of this are not pretty.
