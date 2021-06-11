# Github tutorial on Github
As a green hand in github, I know how to use git to manage my code. However, I don't get how to use this in the real cases. So, I write the markdown file in the repository to record how I learn to use this fantastic tool.

## What's Github
At first, what would you prefer, "on", "in", or "at" github? The answer should be "on". Here is the [answer](https://ell.stackexchange.com/questions/89101/in-on-or-at-github).

Ok, let's go back to the topic. Here are some definitions of the items about github.

**Repository**: It is just like a project, you can save your codes about one project in the same repository.

**Star**: You star a project means you like the project and put into your "favorite" folder.

**Fork**: Copy the project to your own account. The edits on the forked repository will not be changed unless you send a request to the owner and the owner accepts.

**Pull request**: When you want to upload your code to the owner of the repository, you can pull request to the owner. When the request is accepted, the edits you make will be shown on the original repository.

**Watch**: Get notifications when the repository is updated.

**Issue**: When you find some bug, you can issue for the discussion.

## Create a repository
Github provides a easy operating interface for users. We are going to use **Git** or Pycharm to initiate a new repository.

## Git Workflow
If you have the privilege to change the target repository, your workflow will be like.

![workflow](image/git_workflow1.jpg)

Here are some brief introductions:
1. **clone**: you can clone a remote repository to the local. It will be used for initiation.
2. **fetch**: get the new code to the local without merge. The edits will be shown in the code.
3. **checkout**: If you have a branch, you can switch branches by checkout.
4. **add**: put the code into the buffer zone before commit.
5. **commit**: submit to the local repo. History will be stored in the local.
6. **pull**: fetch and merge. the updated code will be in both local repo and workspace.
7. **push**: update the code to the remote repo.

When you want to get evolved in some repository of which you don't have the privilege, your workflow will be like.

![workflow](image/git_workflow2.png)

The steps are similar to the previous one. However, you need to first fork the repository to your own account. After you finished changing, you need to pull request to make your code updated to the original one.

## Download Git
Before we start using Git, we need to download it in your computer. Also, you can download Git from your IDE. However, it would be great if you can download on your computer directly. The IDE can automatically track your Git and use it.

You can download Git from the [link](https://git-scm.com/downloads). When you right click and find Git GUI and Git Bash, it indicates you install successfully.

## Configure Git
There are some methods to log in your account.
1. Use IDE. When you first use Git in Pycharm, there will be a window to log-in. The software will remember your account and password.
2. Use command lines. You can do this in Git Bash and any terminal.
```angular2html
git config --global user.name "your name"
git config --global user.email "your email"
## chekc your information
git config --global user.name
git config --global user.email
```