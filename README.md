Basic Setup and Initialization
git --version: Verifies that Git is installed on your machine (0:11:13).
git init: Initializes a new, empty Git repository in the current directory (0:14:41).
git clone [url]: Downloads an entire repository from a remote source like GitHub to your local machine (0:18:05).
Staging and Committing
git status: Checks the current status of your project, showing which files are modified, staged, or untracked (0:20:20).
git add [file] / git add . / git add -A: Adds changes from the working directory to the staging area (0:21:43 - 0:23:40).
git reset: Unstages files, moving them back from the staging area to the working directory (0:24:30).
git commit -m "message": Permanently saves your staged changes to the local repository with a descriptive message (0:30:22).
git config --global user.name/email: Sets your identity for Git commits (0:32:00).
git reset HEAD: Undoes the last commit (0:34:13).
Managing Files
git rm [file]: Removes a file from the repository and stages the deletion (0:35:32).
git rm --cached [file]: Removes a file from the staging area but keeps it in your local working directory (0:37:00).
git rm -r [folder]: Recursively removes a folder and its contents (0:38:50).
History and Navigation
git log: Displays the commit history (0:39:50).
git log --oneline: Shows a condensed, one-line summary of commit history (0:40:37).
git checkout [branch/commit-id]: Used to switch between branches or move to a specific past commit (0:43:53, 0:52:13).
Branching and Merging
git branch: Lists all branches in the repository (0:43:07).
git branch [name]: Creates a new branch (0:43:18).
git merge [branch]: Combines the history of a specified branch into your current branch (0:45:50).
Remote Synchronization
git push: Uploads your local commits to the remote repository (0:57:18).
git fetch: Downloads changes from the remote repository without merging them into your working files (0:58:43).
git pull: Fetches and immediately merges changes from the remote repository (0:59:45).
Advanced Workflows
git restore: Discards local changes to a file (1:00:24).
git stash: Temporarily shelves unfinished changes so you can work on something else (1:03:16).
git stash pop / apply: Restores stashed changes (1:08:26).
git revert [commit-id]: Creates a new commit that reverses the changes of a previous commit (1:09:47).
git rebase: Reapplies commits on top of another base tip, often used to clean up history (1:12:18).
