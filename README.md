# SE-Git-hw

## Overview

This repository was created for a Software Engineering assignment focused on using Git and GitHub for version control and collaborative software development.

The project demonstrates:

- Creating an initial Git commit
- Working with Git branches
- Adding a new feature
- Committing and pushing changes
- Creating and merging pull requests
- Using GitHub Issues
- Linking issues with development work
- Simulating and resolving a merge conflict
- Synchronizing changes between branches

## Repository Structure

```text
SE-Git-hw/
├── HelloWorld.java
├── apple.py
└── README.md
```

## Programs

### HelloWorld.java

The initial program created for the repository is a simple Java Hello World program:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

To compile and run:

```bash
java HelloWorld
```

### apple.py

`apple.py` was added as a feature on the `feature-1` branch.

```python
print("I eat apple")
```

To run the program:

```bash
python3 apple.py
```

## Git Workflow

The project followed a feature-based Git workflow.

### Initial Commit

The initial Hello World program was committed to the repository:

```text
34f8cc0 Initial commit with Hello, World! program
```

### Feature Branch

A separate branch named `feature-1` was used to develop the `apple.py` feature.

The feature was committed with:

```text
09f2e72 added apple.py
```

The branch was then pushed to GitHub and used to create a pull request into `main`.

### Pull Requests

The project includes multiple pull request merges in its Git history:

```text
e1a5407 Merge pull request #1 from samtuga1/feature-1
8e9a4b4 Merge pull request #2 from samtuga1/wasif-feature
```

These demonstrate the use of GitHub pull requests to merge changes into the main branch.

## Merge Conflict

A merge conflict was intentionally simulated during the project by making conflicting changes across branches.

The conflict was resolved manually and committed with:

```text
0f822aa Resolved conflict
```

The history also contains the merge operation:

```text
2fa6bf2 Merge branch 'main' into wasif-feature
```

The conflict-resolution process involved identifying the conflicting changes, selecting the appropriate version, removing Git's conflict markers, staging the corrected file, and committing the resolution.

## GitHub Issues

GitHub Issues were used to track development tasks.

Issue #5 was associated with development work and closed through a commit:

```text
1377c10 closes issue #5
```

GitHub issues can also be linked to pull requests using keywords such as:

```text
Fixes #5
```

or:

```text
Closes #5
```

This connects the development work to the corresponding issue and allows GitHub to automatically close the issue when the associated pull request is merged.

## Useful Git Commands

### Check repository status

```bash
git status
```

### View branches

```bash
git branch
```

### Create a new branch

```bash
git checkout -b feature-1
```

### Switch branches

```bash
git checkout main
```

### Stage changes

```bash
git add .
```

### Commit changes

```bash
git commit -m "Commit message"
```

### Push changes

```bash
git push
```

### Pull changes from main

```bash
git pull origin main
```

### Fetch remote changes

```bash
git fetch origin
```

### View commit history

```bash
git log --oneline --all --decorate
```

## Learning Outcomes

Through this project, I gained practical experience with Git and GitHub, including:

1. Creating and managing commits
2. Creating and switching between branches
3. Developing features independently
4. Pushing branches to GitHub
5. Creating pull requests
6. Using GitHub Issues
7. Linking issues to development work
8. Understanding merge conflicts
9. Resolving merge conflicts
10. Maintaining a project using version control

## Author

**Samuel Twumasi**
