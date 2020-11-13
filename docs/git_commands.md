# Basic git commands

### Help

    git <command> -h

### Clone

Clones the repository to the local directory

    git clone <url>

### Add

Adds file to the staging index

    git add <path/file>

Adds all modified tracked files to the staging index

    git add *

### Remove

Removes tracked file from the git index

    git rm <path/file>

Recursively removes the tracked directory from the git index

    git rm -r <path/directory>

Dry run simulates what would happen after executing the  remove command

    git rm --dry-run <path/filename>

### Commit

Commits all changes and adds commit message to the git log

    git commit -m "<Commit Message>"

### Push

Push the local repository to the origin repository

    git push -u origin <branch>

### Pull

Update local working branch with remote commits

    git pull

Update local working branch with remote commits but rewrite history so local commits occur after remote commits

    git pull --rebase

### Branch

Creates a new branch

    git branch <branch_name>

Lists all branches

    git branch

Changes working directory to the specified branch

    git checkout <branch_name>

Creates a new branch and changes working directory to the specified branch

    git checkout -b <branch_name>

Deletes branch

    git branch -d <branch_name>

### Merge

    git merge <branch_name>

### Diff

Compares uncommitted changes and the last commit

    git diff

Compares two commits using the hash values

    git diff <hash_a> <hash_b>

Compares file across two branches

    git diff <branch_a>  <branch_b>  <path/file>

## Commit History

Shows commit history

    git log

Shows commit history in a single line

    git log --oneline