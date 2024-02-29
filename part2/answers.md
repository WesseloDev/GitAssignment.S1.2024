## Part 2: Questions
#### 1. List three major version control for software engineering.
1. Git
2. Perforce
3. Mercurial

#### 2. What are the main advantages to using Git in your software development, and how is it useful for game developers?
Some of the main advantages of using Git for software development is that it allows you to collaborate with other coders on the same project, and it lets you view the history of everything that has been added to the project, who added it, and when.

It's useful for game developers because collaborating on projects is an important part of game development. It's also useful because if an error is introduced, or if a lot of important files are deleted, you can revert to an earlier version.

#### 3. Define the following terms in relation to Git: branch, pull, push, repository, working copy, merge

- branch: a separate copy of your repository, that can have different changes made in comparison to your main or other branches. It serves as a snapshot of a specific point of your repository that you can make changes to from there, or merge into other branches.
- pull: asking for the most up to date version of your repository, and receiving all of the changes and new files that have happened since you last pulled.
- push: sending any changes that you've made to your repository.
- repository: the place that stores your code and files for the project that you're currently working on. It tracks and saves all of the changes that are made to it.
- working copy: a local repository on your computer. The changes made on your working copy won't show up in the repository unless you commit and push the changes.
- merge: combining two different branches into one. The changes made in one branch will be added to another branch.

#### 4. If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.
- WHS
- Copyright

#### 5. Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.
- vimdiff
- opendiff
- kdiff3
- tortoisemerge
- araxis
- code compare

#### 6. In a merged source code file, how does Git let you know there is a conflict?
When you try to merge a file with conflicting changes, Git will tell you that there is a conflict in that file and will not merge the branches.

#### 7. What are the steps you can take to resolve Git conflicts?
1. Find out what files are affected by the merge conflict - you can do this by running git status in your working copy.
2. Open the file in Visual Studio Code or another text editor.
3. Navigate to the conflict. There will be a ``<<<<<<<`` where the conflict starts, and a ``=======`` separating the changes from the main branch and your current branch.
4. Decide which change you want to keep, or make a new change.
5. Delete the ``<<<<<<<``, ``=======``, and ``>>>>>>>``, and make your change.
6. Stage your changes and commit them.
7. You can now merge your conflicting branches.

#### 8. What does git revert do, and how can you use it?
git revert makes a new commit that removes the changes of a given commit. You can use it to revert a commit that somebody made that added a bug or some faulty code.

#### 9. What does git reset do, and how can you use it? 
git reset undoes all changes made to a local repository up to a specified commit. You can use it to revert multiple commits at once and go back to a previous point.

#### 10. What is the difference between git revert and git reset?
git revert only reverts the changes of one commit. git reset can revert the changes of multiple commits.

#### 11. True or False: It is okay to commit broken code to the main branch.
False

#### 12. True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.
True

#### 13. What is DevOps, how is it useful for game developers?
DevOps is a methodology that intends to create a more cohesive and high-speed development cycle by integrating and automating the work of software development and operations. It's useful for game developers because it makes game development more efficient and reliable. It also automates building, testing and deployment of games.

#### 14. List what tools can be used with DevOps. Give a brief description of each one. (at least 3)
1. Jenkins - a program that lets developers build and test their projects, and makes it easier to integrate changes to the project.
2. Git - a version control system that's used for managing source code, and can be used for collaborative development.
3. Maven - a build automation and project management tool that streamlines compilation, testing, packaging and distribution.

#### 15. What is CI/CD and how can it be used to automate the game development process?
CI/CD stands for continuous integration and continuous deployment. Small code changes are made frequently, and automatic steps taken to make sure that the code is reliable. The code is then delievered. In the game development process, it can be used to automatically make new builds when you make changes to your code, allowing you to test things a lot quicker, have a history of your builds, or send your builds somewhere like itch or Steam to let beta testers try out your builds.