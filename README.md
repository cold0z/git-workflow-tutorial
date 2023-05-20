# git-workflow-tutorial

## Git Workflow Tutorial 🚀
This tutorial will guide you through a simple Git workflow using the command line. By following these steps, you will learn the basics of version control, including creating a repository, making commits, branching, merging, and pushing changes to a remote repository.

## Prerequisites
Before you begin, ensure that you have Git installed on your local machine. You can download and install Git from the official website: https://git-scm.com/downloads.

## Getting Started
Create a Repository: Start by creating a new directory on your local machine. Open the command line or terminal, navigate to the directory, and run the following command to initialize a new Git repository:

```
git init
```
Create Sample Folders: Create two sample folders inside the repository directory, named "src" and "docs". You can use the following commands:

```
mkdir src
mkdir docs
```

Create a File: Inside the "src" folder, create a new file named "app.py". You can use any text editor of your choice.

Stage and Commit Changes: Add the file to the staging area using the following command:

```
git add src/app.py
```

After adding the file, commit the changes with a descriptive message:

```
git commit -m "Initial commit"
```

Create a Branch: It's a good practice to work on different branches for different features or tasks. Create a new branch using the following command:

```
git branch feature/add-functionality
```
This will create a new branch named "feature/add-functionality".

Switch Branches: Switch to the newly created branch using the following command:

```
git checkout feature/add-functionality
```
This will allow you to make changes specific to this branch.

Make Changes: Open the "app.py" file in the "src" folder and make some modifications. Save the changes when you're done.

Stage and Commit Changes Again: Stage the modified file and commit the changes:

```
git add src/app.py
git commit -m "Update app functionality"
```
Merge Branches: After completing your changes on the new branch, you may want to merge it back into the main branch (often called master or main). To do this, switch back to the main branch:

```
git checkout main
```
Then, merge the changes from the other branch:

```
git merge feature/add-functionality
```


Push Changes to Remote: If you want to share your changes with others or store them remotely, you need to push your commits to a remote repository. To do this, create a new repository on a Git hosting service (e.g., GitHub, GitLab), and obtain the URL for the remote repository.

Then, add the remote repository to your local repository using the following command:

```
git remote add origin <remote-url>
```
Replace <remote-url> with the URL of your remote repository.

Push Commits: Finally, push your changes to the remote repository:

```
git push -u origin main
```
This will push your commits to the main branch on the remote repository. Subsequent pushes can be done with git push.

## Conclusion

Congratulations! You have completed a simple Git workflow using the command line. This tutorial covered the basic steps of creating a repository, making commits, branching, merging, and pushing changes to a remote repository. By following this workflow, you can effectively manage your codebase and collaborate with others using Git.

Feel free to explore more advanced Git features and workflows as you continue your journey with version control. Git offers a wide range of powerful capabilities, such as resolving merge conflicts, reverting changes, and working with remote branches. The more you use Git, the more comfortable you will become with its features and the more efficiently you will be able to work on your projects.

Remember to refer to the official Git documentation (https://git-scm.com/doc) whenever you need more information or guidance on specific Git commands and concepts.

Happy coding and happy Git-ing!
