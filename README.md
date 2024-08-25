# Git Assignment - <aaron6yi

a. What is an issue?

An issue is a tool used to track tasks, report bugs, request features, or discuss ideas within a project on platforms like GitHub. It allows team members to collaborate by discussing and managing tasks related to the project. Issues help organize and prioritize work and can be linked to pull requests and other issues to show how different tasks are connected.

b. What is a pull request?

A pull request is a proposal to merge changes from one branch into another within a repository. It enables team members to review, discuss, and approve or reject changes before they are added to the main codebase. Pull requests are essential for collaborative workflows, particularly in open-source projects, as they facilitate code review and ensure that multiple developers can work together smoothly.

c. Describe the steps to open a pull request?

To open a pull request, first create a new branch where you will make your changes. After making and committing your changes, push the branch to the remote repository on GitHub. Then, navigate to your repository on GitHub, where you’ll see an option to create a pull request from the branch you just pushed. Click "Compare & pull request," add a title and description, review the changes, and submit the pull request.

d. Describe the steps to add a collaborator to a repository (share write permissions)

To add a collaborator to a GitHub repository, go to the repository and click on "Settings." In the settings menu, select "Collaborators and teams" or "Manage access." Click the "Invite a collaborator" button, then enter the person’s GitHub username or email. Once you find the user, click "Add" to send the invitation. The collaborator will need to accept the invitation to gain write access to the repository.

e. What is the difference between git and GitHub?

Git is a distributed version control system that developers use to track changes in their codebase, manage different versions, and collaborate with others. It works locally on your machine. GitHub, on the other hand, is a cloud-based platform built on top of Git that hosts Git repositories online, providing additional features like issue tracking, pull requests, and collaboration tools, making it easier to share and collaborate on projects.

f. What does git diff do?

The git diff command shows the differences between files or commits in a Git repository. It compares the changes in your working directory with the staging area or between commits, displaying what has been added, modified, or removed. This is useful for reviewing changes before committing them or comparing different versions of the code.

g. What is the main branch?

The main branch, often called "main" or "master," is the default branch in a Git repository where production-ready code is stored. It acts as the central branch where all other branches eventually merge. Typically, feature branches are created from the main branch and merged back into it after review and testing.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

After the initial commit, it’s generally better to avoid pushing changes directly to the main branch. Instead, create a separate branch for your changes, push that branch to the remote repository, and open a pull request to merge the changes into the main branch. This practice helps maintain code quality, avoid conflicts, and keep the main branch stable and deployable.
