# Experiment 1 — Starting a Git Repository

Commands executed one at a time in the terminal.

## I. Create and open a project folder

```bash
mkdir git-practical
cd git-practical
```

## II. Initialize the repository

```bash
git init
```

## III. Check the repository status

```bash
git status
```

## IV. Create a sample file

```bash
echo "<h1>My First Git Project</h1>" > index.html
```

## V. Stage the file

```bash
git add index.html
```

## VI. Commit the staged file

```bash
git commit -m "Initial commit"
```

## VII. View the commit history

```bash
git log --oneline
```

## Input

- Project folder name: `git-practical`
- File created: `index.html`
- File content: `<h1>My First Git Project</h1>`
- Commit message: `Initial commit`

## Output

```
Initialized empty Git repository in .../git-practical/.git/

On branch main
No commits yet
Untracked files:
  index.html

[main (root-commit) abc1234] Initial commit
 1 file changed, 1 insertion(+)

abc1234 Initial commit
```

## Result

The local Git repository was created successfully. The sample file was added to the
staging area and saved in the repository as the first commit.
