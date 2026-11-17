# Experiment 2 — Pushing and Cloning a Repository Using Git and GitHub

## Part A — Pushing a Local Repository

### Step 1: Create a project folder

```bash
mkdir git-push-practical
cd git-push-practical
```

### Step 2: Initialize Git

```bash
git init
```

### Step 3: Create a sample file

```bash
echo "My first GitHub project" > README.md
```

### Step 4: Stage the files

```bash
git add .
```

### Step 5: Commit the changes

```bash
git commit -m "Initial commit"
```

### Step 6: Connect to the GitHub repository

```bash
git remote add origin https://github.com/USERNAME/REPOSITORY.git
```

### Step 7: Set the main branch

```bash
git branch -M main
```

### Step 8: Push the changes

```bash
git push -u origin main
```

## Part B — Cloning a Repository

### Step 1: Copy the HTTPS URL of an existing GitHub repository

### Step 2: Clone the repository

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
```

### Step 3: Navigate into the cloned folder

```bash
cd REPOSITORY
```

### Step 4: Check repository status

```bash
git status
```

### Step 5: View the remote repository details

```bash
git remote -v
```

## Result

The local repository was pushed to GitHub successfully and an existing remote
repository was cloned to the local computer.
