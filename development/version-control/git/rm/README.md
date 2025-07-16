### git rm

**Usage:** Remove files from repository index and local filesystem. <br />
More information: https://git-scm.com/docs/git-rm. <br />

Remove file from repository index and filesystem:

```
git rm path/to/file
```

Remove directory:

```
git rm -r path/to/directory
```

Remove file from repository index but keep it untouched locally:

```
git rm --cached path/to/file
```
