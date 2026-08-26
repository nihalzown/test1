# Basic Git Commands Guide

This README provides a comprehensive list of basic Git commands to help you manage your version control effectively.

## 1. Setup and Configuration
- `git config --global user.name "[name]"`: Sets the name you want attached to your commit transactions.
- `git config --global user.email "[email address]"`: Sets the email you want attached to your commit transactions.

## 2. Starting a Project
- `git init`: Initializes a new, empty Git repository in the current directory.
- `git clone [url]`: Downloads an existing project and its entire version history from a remote server (e.g., GitHub, GitLab).

## 5. Sharing and Updating Projects
- `git remote add origin [url]`: Connects your local repository to a remote server.
- `git push -u origin [branch-name]`: Uploads local repository content to a remote repository and sets the upstream tracking.
- `git pull`: Fetches and merges changes from the remote repository to your current working directory.
- `git fetch`: Downloads all history from the remote tracking branches without merging them into your local branch.

## 6. Reviewing History
- `git log`: Lists version history for the current branch.
- `git log --oneline`: Shows a compact version of the commit history (one line per commit).

## 7. Undoing Changes
- `git revert [commit-hash]`: Creates a new commit that undoes all of the changes made in a specific commit, preserving the history.
- `git reset [commit-hash]`: Undoes all commits after the specified commit, preserving changes locally.
- `git restore [file]`: Discards changes in the working directory for a specific file.
