### git clean

**Usage:** Remove files not tracked by Git from the working tree. <br />
More information: https://git-scm.com/docs/git-clean. <br />

Delete untracked files:

```
git clean
```

Interactively delete untracked files:

```
git clean --interactive
```

Show which files would be deleted without actually deleting them:

```
git clean --dry-run
```

Forcefully delete untracked files:

```
git clean --force
```

Forcefully delete untracked [d]irectories:

```
git clean --force -d
```

Delete untracked files, including e[x]cluded files (files ignored in .gitignore and .git/info/exclude):

```
git clean -x
```
