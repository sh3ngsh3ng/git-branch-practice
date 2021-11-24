Branch Commands:

1) List all branch
```
git branch
```

2) Create New Branch
```
git branch <new-branch>
```

3) Deleting Branch
```
git branch -d <branch-name>
```

4) Switch Branch
```
git checkout <branch-name>
```

5) Switch + Create New Branch (shortcut)
- -b tells git to create new branch before checking out
```
git checkout -b <new-branch>
```
6) Merging (3 steps)

    - Confirm the receiving branch
        ```
        git checkout main
        ```
    - Fetch latest remote commits
    - Merge
        ```
        git merge <branch-name>
        git branch -d <branch-name> (to delete the old branch)
        ```