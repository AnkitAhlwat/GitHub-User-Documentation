# Working with Git and managing code on GitHub

Git is a opened source version control system used alongside GitHub. This section will help you work with Git and manage your code on GitHub. You will learn the most commonly used Git commands and when to use them.

## Install and configure Git

1. Download and install Git from the [**official website**](https://git-scm.com/downloads).
- Configure Git with your username and email using the terminal:

    ```git
    git config --global user.name "Your Name"
    git config --global user.email "your.email@example.com"
    ```

!!! tip "Tip"
Make sure to replace "Your Name" and "your.email@example.com" with your actual name and email address. This ensures that your github looks professional and it's easy for others to find your work.

## Clone a repository locally

When we clone a repository we make a identical copy, including all folders and every version of files, from the data stored on Github at the time of cloning. There are several ways to do this, the easiest is by copying the URL. 

1. Navigate to the GitHub repository you want to clone.
- Click on the **Code** button and copy the URL.
- Open a terminal and navigate to your desired location.
- Run the following command:

    ```git
    git clone <repository_url>
    ```

By default the clone command will save the repository in a local folder on your computer which has the same name as the original repository you cloned. 

5. To specify a folder name you can add it after the URL.

    ```git
    git clone <repo> <directory>
    ```

##  Create and switch branches

1. Branches are used so many developers can work on the same project simultaneously without affecting the main codebase.

2. To create a new branch, make sure you are in the correct project folder and run:

    ```git
    git checkout -b <new_branch_name>
    ```

3. To switch between branches, run:

    ```git
    git checkout <branch_name>
    ```

## 4️⃣ Stage and commit changes

- Before pushing your changes you must first stage them. This is useful as you can specify which files you wish to commit. The . syntax includes all changes.

- Stage the changes:

```git
git add .
```

- Commit the changes:

```git
git commit -m "Your descriptive commit message"
```

## 5️⃣ Write commit message

- Write clear, concise, and descriptive commit messages that summarize the changes made in the commit.

!!! warning "Warning"
Make sure your commit message begins with a imperative verb. This is considered best practice as it allows for others to quickly understand the purpose of your commit.

## 6️⃣ Pull remote changes

- To update your local branch with the latest remote changes, run:

```git
git pull
```

## 7️⃣ Resolve merge conflicts

- Merge conflicts occur when multiple people alter the same lines of code in a repository and then attempt to merge these changes together.
- When you encounter conflicts, edit the affected files to resolve the issues.
- Stage and commit the resolved changes.

!!! tip "Tip"
Make sure to always pull any changes before beginning to work on a codebase. This will reduce the likelihood of merge conflicts occurring.

## 8️⃣ Push changes remotely

- To push your changes to the remote repository, run:

```git
git push
```

## 9️⃣ Navigate commit history

- To view the commit history, run:

```git
git log
```

## 🔟 Undo or modify commits

- To undo or modify commits, use commands like

```git
revert`, `git reset`, or `git rebase
```

&nbsp;

# Conclusion and recap

By the end of this section, you will have successfully learned the following:

- How to install and configure Git
- How to clone a repository and work with branches
- How to stage, commit, and push changes to GitHub
- How to navigate commit history and resolve conflicts

**Great job!** You are now familiar with essential Git commands and best practices for managing your code on GitHub.
