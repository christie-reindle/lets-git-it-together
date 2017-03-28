# GitHub Flow and Collaboration
This repository serves as a step-by-step guide for project workflow, after project creation.

1. Find your teams respository on GitHub and clone the respository using Git Shell/Terminal. 
Note: Do **not** fork the main repository.
  - `git clone [project name]`
  - `cd [project name]`
2. Create a branch from the repository using Git Shell/Terminal.
  - `git checkout -b feature/task-name`
3. Push up newly created branch using Git Shell/Terminal
  - `git push -v origin feature/task-name`
3. Create, edit, rename, move, or delete files.
4. Create commits once crucial parts of the task has been completed. 
  - `git status`
  - `git add [individual file name]`
  - `git commit -m "Brief detailed message"`
  - `git push`
5. Send and create a [pull request](https://help.github.com/articles/about-pull-requests/) from your branch with the **base** being the master and the compare being **feature/task-name**.
6. Notify the PM that you have sent a pull request and wait for the PM to [merge the pull requests](https://help.github.com/articles/merging-a-pull-request/)

## Your Task
With the students on your table acting as a team,
1. Assign one student as the PM, this student is in charge of creating the repository on GitHub and adding every other student on the table as collaborators.
2. Every other student must accept the invitation to become a collaborator on GitHub.
3. Each student must **clone** the repository to their local workspace.
4. Follow the GitHub Flow above to create a simple project. Each student is only allowed to create and modify one file each. 
4. Create the following files:
  - index.html
  - css/styles.css
  - js/app.js
5. These files must be connected to one another and display the team name in the **title**, background color of **blue**, and a button that gives an alert "Hi" in the Console upon click.

Resources
- [Understanding Github Flow](https://help.github.com/articles/github-flow/)
- [Illustrated Guide to GitHub Flow](https://guides.github.com/introduction/flow/)
- [Creating a new respository](https://help.github.com/articles/creating-a-new-repository/)
- [Adding Collaborators to GitHub Project](https://help.github.com/articles/inviting-collaborators-to-a-personal-repository/)
- [Resolving Merge Conflicts on GitHub](https://help.github.com/articles/resolving-a-merge-conflict-on-github/)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)