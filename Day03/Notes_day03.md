## day 03

#### Git is a popular version control system that enables developers to collaborate on projects effectively. It has a wide range of functionalities, including the ability to create branches, view commit history, remove and move assets, and clone or fork repositories. In this note, we'll discuss each of these features in detail.

### Introducing Branches and Their Usage

- Branches are a fundamental part of Git that allow developers to work on separate parts of a project simultaneously. They are essentially separate snapshots of a repository that can be modified and merged back into the main branch later. Here's how to create, switch to, and merge branches using Git:

- Creating a Branch: To create a new branch, use the git branch command followed by the name of the new branch. For example, to create a branch called "feature-branch," you'd run git branch feature-branch.
- Switching to a Branch: To switch to a different branch, use the git checkout command followed by the name of the branch. For example, to switch to the "feature-branch" we just created, you'd run git checkout feature-branch.
- Merging Branches: To merge changes from a branch back into the main branch, use the git merge command followed by the name of the branch. For example, to merge changes from the "feature-branch" back into the main branch, you'd run git merge feature-branch.


### Viewing Commit History Locally and on GitHub

Git maintains a record of all changes made to a repository in the form of commits. These commits contain information such as who made the changes, when they were made, and what changes were made. To view commit history, you can use the git log command. By default, git log will display the commit history for the current branch.

If you want to view commit history on GitHub, navigate to the repository's page, and click on the "commits" tab. This will display a chronological list of all the commits made to the repository, along with their associated messages.

### Removing and Moving Assets with git rm and git mv

Git provides two commands for removing and moving assets: git rm and git mv. Here's how to use them:

- Removing Assets: To remove a file from the repository, use the git rm command followed by the name of the file. For example, to remove a file called "example.txt," you'd run git rm example.txt.
- Moving Assets: To move a file from one location to another within the repository, use the git mv command followed by the current name of the file and the desired name of the file. For example, to move a file called "old.txt" to "new.txt," you'd run git mv old.txt new.txt.


### Introducing Cloning and Forking

Cloning and forking are two ways to create a copy of a Git repository. Here's what each of them means:

- Cloning: Cloning creates a local copy of a repository that can be modified and synced with the remote repository. To clone a repository, use the git clone command followed by the URL of the remote repository. For example, to clone a repository located at "https://github.com/example/repo," you'd run git clone https://github.com/example/repo.
- Forking: Forking creates a copy of a repository on your GitHub account, allowing you to modify it without affecting the original repository. To fork a repository, navigate to the repository's page on GitHub and click on the "fork" button in the top right corner.


In summary, Git is a powerful tool that offers many functionalities for managing version control. By learning how to use branches, view commit history, remove and move assets, and clone or fork repositories, developers can effectively collaborate and manage their codebase. It's important to note that these are just a few of the many functionalities offered by Git, and there's much more to learn about this powerful tool. By taking the time to understand how Git works and practicing using its various features, developers can become more efficient and effective at managing their projects.