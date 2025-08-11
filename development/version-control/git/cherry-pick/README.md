### git cherry-pick

**Usage:** Apply the changes introduced by existing commits to the current branch. <br />
**More information:** https://git-scm.com/docs/git-cherry-pick. <br />

Apply a commit to the current branch:

```
git cherry-pick commit
```

Apply a range of commits to the current branch (see also: git rebase --onto):

```
git cherry-pick start_commit~..end_commit
```

Apply multiple (non-sequential) commits to the current branch:

```
git cherry-pick commit1 commit2 ...
```

Add the changes of a commit to the working directory, without creating a commit:

```
git cherry-pick --no-commit commit
```
