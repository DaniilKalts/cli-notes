Search for a string in tracked files.
- You can add `-n` option to include the line(s) where the occurance was found.

```
git grep -n search_string
```

Search for a string in a specified tracked file.

```
git grep search_string -- filename
```

Search for a string across all branches

```
git grep search_string $(git rev-list --all)
```
