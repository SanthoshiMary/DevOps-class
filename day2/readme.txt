# DevOps Day 2

## Objective

To learn and practice Git version control concepts and basic Docker commands.

---

# Part 1 - Git

## 1. Git Branching

### Check Git Status

    git status

Used to check the current state of the Git repository.

### Create a Branch

    git branch master

Used to create a new branch named `master`.

### Check Available Branches

    git branch

Used to view the available branches and identify the current branch.

### Switch to Master Branch

    git checkout master

Used to switch from the current branch to the `master` branch.

### Create a File

    vi day2.txt

Created a file named `day2.txt` for branch practice.

### Check Files

    ls

Used to list the files in the current directory.

### Check Git Status

    git status

Used to check the status of the newly created file.

---

## 2. Git Stash

### Stash Changes

    git stash -u

Used to temporarily save changes, including untracked files.

The `-u` option includes untracked files in the stash.

### Remove File

    rm day2.txt

Used during the practice to remove the file from the working directory.

---

## 3. Git Commit

### Create Initial File

    vi initial.txt

Created `initial.txt` for the initial commit.

### Add File

    git add initial.txt

Added the file to the staging area.

### Commit

    git commit -m "Initial commit"

Created the initial commit in the repository.

---

## 4. Git Branch Practice

### Create Master Branch

    git branch master

Created the `master` branch.

### Switch to Master

    git checkout master

Switched to the `master` branch.

### Create Day 2 File

    vi day2.txt

Created `day2.txt` on the `master` branch.

### Switch to Main

    git checkout main

Switched back to the `main` branch.

### Add File

    git add day2.txt

Added `day2.txt` to the staging area.

### Commit File

    git commit -m "Add day2 text file"

Committed `day2.txt` to the `main` branch.

### View Commit History

    git log

Used to view the commit history of the current branch.

### Switch to Master

    git checkout master

Switched back to the `master` branch.

### View History

    git log

Used to verify the commit history of the `master` branch.

### List Files

    ls

Used to verify the files available in the current branch.

---

## 5. Git Merge

### Switch to Main

    git checkout main

Switched to the `main` branch.

### Check Branches

    git branch

Used to view the available branches.

### Merge Master

    git merge master

Used to merge the changes from the `master` branch into the `main` branch.

### View History

    git log

Used to check the commit history after the merge.

---

## 6. Git Rebase

### Clear Terminal

    clear

Used to clear the terminal screen.

### Create Rebase File

    vi rebasefile

Created a file named `rebasefile` for rebase practice.

### List Files

    ls

Used to check the files in the repository.

### Add File

    git add rebasefile

Added `rebasefile` to the staging area.

### Check Status

    git status

Used to check the current repository status.

### Commit Rebase File

    git commit -m "rebase practice"

Created a commit for rebase practice.

### View Commit History

    git log

Used to view the commit history.

### Switch to Master

    git checkout master

Switched to the `master` branch.

### Rebase

    git rebase main

Used to replay the commits from the current branch on top of the `main` branch.

### View History After Rebase

    git log

Used to verify the commit history after the rebase.

### Check Files

    ls

Used to verify the files after the rebase operation.

---

# Part 2 - Docker

## 1. Check Docker Version

    docker -v

Used to check the installed Docker version.

## 2. Docker Node

    docker node

Used to display Docker Swarm node information.

## 3. Search for Node Image

    docker search node

Used to search for Node.js images available on Docker Hub.

## 4. Pull Node Image

    docker pull node

Used to download the Node.js image from Docker Hub.

## 5. List Docker Images

    docker images

Used to display the Docker images available locally.

## 6. Search for Apache Images

    docker search apache2
    docker search httpd

Used to search for Apache HTTP Server images on Docker Hub.

## 7. Pull Apache HTTP Server Image

    docker pull httpd

Used to download the Apache HTTP Server image.

## 8. Create an Apache Container

    docker create httpd

Used to create a container from the `httpd` image.

## 9. List All Containers

    docker ps -a

Used to display all Docker containers, including running and stopped containers.

## 10. Start the Apache Container

    docker start nervous_lichterman

Used to start the Apache HTTP Server container.

## 11. Check Running Containers

    docker ps

Used to display the currently running Docker containers.

---

# Concepts Learned

## Git

- Git Status
- Git Branch
- Git Checkout
- Git Add
- Git Commit
- Git Log
- Git Stash
- Git Merge
- Git Rebase
- Branch Management

## Docker

- Docker Image
- Docker Container
- Docker Hub
- Docker Pull
- Docker Create
- Docker Start
- Docker PS
- Apache HTTP Server (`httpd`)
- Node.js Docker Image

---

# Git Concepts

### Git Stash

Temporarily saves changes without creating a commit.

### Git Merge

Combines changes from one branch into another branch.

### Git Rebase

Replays commits onto another branch to create a more linear commit history.

---

# Result

Successfully practiced Git branching, Git stash, Git commit, Git merge,
and Git rebase operations.

Also practiced basic Docker commands including searching for images,
pulling images, creating containers, starting containers, and checking
running containers.

---

