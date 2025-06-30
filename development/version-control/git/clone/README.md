Clone an existing repository into a new directory (the default directory is the repository name).
- You can add `-q` option to exclude messages during clonning process.

```
git clone remote_repository_location path/to/directory
```

Clone an existing repository with a history including only the latest commit.
- It saves time
- It uses less memory

```
git clone --depth=1 https://github.com/roadmapsh/deprecated-version min-depth
```
