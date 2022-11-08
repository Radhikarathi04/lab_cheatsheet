# Git Cheatsheet

## Glossary

| Keywords                        | Description                                                                                                                                                          |
|---------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| git                             | Open-source distributed version-control system, used to store code in repositories                                                                                   |
| GitHub                          | Platform for hosting and collaborating on Git repositories                                                                                                           |
| SSH (Secure Shell Protocol) Key | Creates connection between your laptop and GitHub. With SSH keys, you can connect to GitHub without supplying your username and personal access token at each visit. |
| staging                         | Proposed files/directories that you'd like to commit                                                                                                                 |
| commit                          | Saving all staged files/directories to your local repository                                                                                                         |
| clone                           | Local version of a repository, including all commits and branches                                                                                                    |
| remote                          | Common repository on eg. Github that all team members to keep that changes in sync with                                                                              |

## Core commands

| Command                            | Description                                                                                                                                                    |
|------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `git init`                         | Creates new local repository                                                                                                                                   |
| `git init [directory/projectname]` | Creates new local repository                                                                                                                                   |
| `git add [file]`                   | Stages specific [file]                                                                                                                                         |
| `git add .`                        | Adds all files in your project to the staging area                                                                                                             |
| `git commit -m "[message]"`        | Commit everything that is staged                                                                                                                               |
| `git status`                       | Shows status of changes as untracked, modified or staged                                                                                                       |
| `git push`                         | Pushes all the commits from the current local branch to its remote equivalent                                                                                  |
| `git log`                          | Shows the commit history for the current repository                                                                                                            |
| `git clone`                        | Creates local copy of remote repository                                                                                                                        |
| `git pull`                         | Downloads all history from the remote branch and merges into the current local branch                                                                          |
| `.gitignore`                       | You can list files/directories that you want to explicitly exclude from Git in a `.gitignore` file. This file should be placed at the root of your repository. |