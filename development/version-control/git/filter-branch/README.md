##### Purge a file from all commits in a repository history

```
git filter-branch --force \
  --index-filter "git rm --cached --ignore-unmatch path/to/file" \
  --prune-empty \
  --tag-name-filter cat \
  -- --all
```
