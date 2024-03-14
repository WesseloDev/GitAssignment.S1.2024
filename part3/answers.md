## Part 3: Git Manual
### Imagine you are working at a game studio, and they want you to help with installing Git.
#### 1. Write instructions on installing git on a windows system.
To install Git on a Windows system, you need to go to the git website at https://git-scm.com/. Navigate to the downloads page, and click on Windows to see the Windows releases. You can then download either the standalone installer, which will install Git for you, or the portable version, which you can keep on a USB and use on any windows computer that meets the minimum requirements for Git.

To run Git on a Windows system, you need to have Windows 7 Service pack 1 or later. 

If you had issues installing Git, you could contact the IT department.

#### 2. Do reserach on some principles/techniques of industry standard best practices creating and working with repositorise and branches in Git.
Some of the best practices for creating and working with repositories are:
- Create a README file
- Have a relevant .gitignore file
- Use Git Large File Storage (Git LFS) for storing large files
- Avoid using git add . without verifying what you're about to add to your repository before pushing
- Review merge requests before accepting them

Some of the best practices for creating and working with branches are:
- Favor making branches over making forks of the repository
- Only merge well-tested, bug-free and production-ready code into the main branch
- Create focused branches that focus on specific tasks
- Use descriptive branch names
- Sync regularly with the main branch
- Clean up and remove old branches

#### 3. List the steps in a Git workflow that the team should follow when working on projects.
Using the Gitflow workflow, you have multiple branches for every stage of development - for example, the main branch, which only has production ready code, the development branch, used to test and bug fix, and the staging branch, used for creating features.
1. Create new features in the staging branch.
2. Merge to the development branch, and test and bug fix the code.
3. Once the code is production ready, merge to the main branch.