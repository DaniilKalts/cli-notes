### git merge

**Usage:** Merge branches. <br />
**More information:** https://git-scm.com/docs/git-merge. <br />

Merge a branch into your current branch:

```
git merge branch_name
```

Edit the merge message:

```
git merge --edit branch_name
```

Merge a branch and create a merge commit:

```
git merge --no-ff branch_name
```

Abort a merge in case of conflicts:

```
git merge --abort
```

Continue a merge after resolving a conflict.

```
git merge --continue
```
