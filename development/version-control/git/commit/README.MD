### git commit

**Usage:** Commit files to the repository. <br />
More information: https://git-scm.com/docs/git-commit. <br />

Commit staged files to the repository with a message:

```
git commit --message "message"
```

Auto stage all modified and deleted files and commit with a message:

```
git commit --all --message "message"
```

Update the last commit by adding the currently staged changes, changing the commit's hash:

```
git commit --amend
```

Commit only specific (already staged) files:

```
git commit path/to/file1 path/to/file2 ...
```
