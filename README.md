# github-3.2-Caroline
## What is GitHub Authentication and how what methods available to be implemented?

GitHub Authentication is the process of verifying your identity and access to GitHub resources. There are different methods available to be implemented, depending on where and how you authenticate to GitHub. Some of the methods are:

- Username and password with two-factor authentication (2FA) or a passkey
- Personal access token
- SSH key
- SAML single sign-on

GitHub recommends using a security key, the GitHub mobile app or an authenticator app as the strongest options for 2FA. These methods provide an extra layer of security for your account and data.


## Contain at least 15 github commands and what are the usage of them?

1. Initializes a new Git repository in the current directory, creating a .git folder to store version control information.

```sh
git init
```

2. Copies a remote repository to your local machine, creating a local copy of the repository for you to work on.

```sh
git clone <repository_url>
```

3. Stages changes for the next commit. You can use git add . to stage all changes in the working directory.

```sh
git add <file>
```

4. Records staged changes in the version history with a descriptive message about the changes made.

```sh
git commit -m "commit message"
```

5. Fetches changes from a remote repository and merges them into your current branch.

```sh
git pull
```

6. Uploads your local commits to a remote repository, making your changes available to others.

```sh
git push
```

7. Lists all the local branches in your repository.

```sh
git branch
```

8. Creates a new branch with the specified name.

```sh
git branch <branch_name>
```

9. Switches to a different branch.

```sh
git checkout <branch_name>
```

10. Combines changes from one branch into the current branch.

```sh
git merge <branch_name>
```

11. Retrieves changes from a remote repository but does not merge them into your local branch.

```sh
git fetch
```

12. Shows the status of your working directory, including untracked files and changes not yet staged for commit.

```sh
git status
```

13. Displays a history of commits in the current branch.

```sh
git log
```

14. Lists the remote repositories connected to your local repository, including their URLs.

```sh
git remote -v
```

15. Initiates the process of creating a pull request on GitHub to propose changes from one branch to another.

```sh
git pull-request
```


## What are the 4 Github commands that you think you will use the most in the real project and why? 

**1. Cloning a Repository**
- The **_git clone <repository_url>_** command is essential for initiating a new project. It copies a remote repository to your local machine, enabling you to start working on the project locally. This command is often the first step when setting up your development environment.

**2. Keeping Local Copy Updated**
- In a collaborative environment, it's crucial to maintain your local copy in sync with the latest changes from the remote repository. The **_git pull_** command fetches these updates and merges them into your current branch. This helps ensure you have the most recent code and assists in resolving conflicts.

**3. Staging and Committing Changes**
- When making updates to your code, you'll frequently use the combination of **_git add <file>_** and **_git commit -m "commit message"_** commands. First, git add stages the changes you want to include in the next commit. Then, **_git commit_** records these changes in the version history with a clear commit message. Consistent commits create a well-documented history of your work, facilitating change tracking and collaboration.

**4. Pushing Changes to the Remote Repository**
- After committing your changes, the **_git push_** command is used to share your work with your project collaborators. Pushing your changes makes them accessible for review, testing, and integration into the primary project. It's a critical step in the collaborative process, ensuring your contributions are visible to the team.


**Thanks for review my work!**
