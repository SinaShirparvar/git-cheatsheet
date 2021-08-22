# git-cheatsheet
dwclass training git
Welcome to the git-cheatsheet wiki!
Working with Git:

1- why should we use control version tools like Git ? 
In order to store all the program's code in one place and have a main source for storing-
program, in which case several programmers can work on a joint project.


2- What is repository ? What important files does a good repository have ? 
A repository is a repository that contains a set of commits and branches, and a good repository includes the following files: README.md, LICENSE, .gitignore  .git

3- What are the parts of a good document ?
.gitignore, README.md LICENSE

4- What does the git clone command do ?
This command is used to get a sample of project in which case we can have the project on our laptop.

5- If we want to update the local repository with the remote repository, which command should be executed ?
$git pull HEAD

6- What is difference between checkout, reset and revert ?
reset: returns the changes and deletes that commit.
revert: after the changes return, a new commit is created.
checkout: the changes are returned but no special work is done, neither the commit is deleted nor added.

7- What is difference between merge and rebase ?
rebse: reapplies commits on top of another base branch.
merge: joins two or more development histories together

8- What command is used to view the history of commites ?
git log

9- which command shows the changes of a file ? 
git show HEAD

10- What is usage of tag ? How to create a tag ?
Used to build versions. When the program's code is complete, we use the appropriate tags, so that we can create a release.

11- What process must be followed to participate in a git-managed project?
reading README.md and .gitignore and LICENSE 
Create a local repository and after performing the necessary tests, we will add commits and apply the changes.

12- What are the branches used for and how can they be integrated?
Branches allow you to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository.
The integration branch is where you bring multiple features together for testing, before the final push onto master.Of course, you don't have to separate things this way. You could do integration on feature branches, just as you could do all your work on master. But separation of concerns is a good thing.

