# git-desktop-lab

## Lab Summary

### 1. Repository Setup
- Created a GitHub repository and cloned it to local via GitHub Desktop.
- Purpose: Learn basic repo setup and clone operations.

### 2. Basic Git Operations
- Added 'info.txt' and edited 'README.md'.
- Purpose: Understand file tracking, committing, and pushing.

### 3. Branching and Merging
- Created 'feature/new-content' branch and added 'content.txt'.
- In GitHub Desktop, created new branch and named it 'feature/new-content'.
- Created 'content.txt' with some text in File Explorer.
- Committed with message: 'Add content.txt with favorite topic'
- Pushed the branch (Push origin).
- On GitHub, did 'Compare & Pull Request' for 'feature/new-content'.
- Added message like “Merging new content into main”.
- Merged Pull Request.
- In GitHub Desktop, switched to main and Fetched origin -> Pull origin to get the latest merge.
- Purpose: Practice branching and merging through pull requests.

### 4. Merge Conflict Resolution
- Created 'branch-a' and 'branch-b' with conflicting changes (README file changes - 'This is branch A', 'This is branch B').
- Pushed branch-a to GitHub, and merge it to main via Pull Request.
- Repeated the same for branch-b and got conflict.
- In GitHub Desktop, for branch-b, Branch -> Update from main -> GitHub Desktop showed the conflict.
- Resolved conflict manually from Notepad++.
- Committed merge. Push 'branch-b' to GitHub, create and merge a pull request to main.
- Conflict resolved by combining changes from both branches.
- Purpose: Understanding of merge conflict resolution in GitHub Desktop.

### Screenshot of Merge Conflict Resolution

- [Merge Conflict Screenshot](conflict_screenshot.png)