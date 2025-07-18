### diff

**Usage:** Compare files and directories. <br />
More information: https://manned.org/diff. <br />

Compare files (lists changes to turn old_file into new_file):

```
diff old_file new_file
```

Compare files, ignoring white spaces:

```
diff --ignore-all-space old_file new_file
```

Compare files, showing the differences side by side:

```
diff --side-by-side old_file new_file
```

Compare files, showing the differences in unified format (as used by git diff):

```
diff --unified old_file new_file
```

Compare directories recursively (shows names for differing files/directories as well as changes made to files):

```
diff --recursive old_directory new_directory
```

Compare directories, only showing the names of files that differ:

```
diff --recursive --brief old_directory new_directory
```

Create a patch file for Git from the differences of two text files, treating nonexistent files as empty:

```
diff --text --unified --new-file old_file new_file > diff.patch
```

Compare files, showing output in color and try hard to find smaller set of changes:

```
diff --minimal --color=always old_file new_file
```
