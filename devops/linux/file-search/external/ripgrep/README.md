### ripgrep

**Usage:** Ripgrep, a recursive line-oriented search tool. Aims to be a faster alternative to `grep`. <br />
More information: https://github.com/BurntSushi/ripgrep/blob/master/GUIDE.md. <br />

Recursively search current directory for a pattern (regular expression):

```
rg pattern
```

Recursively search for a pattern in a file or directory:

```
rg pattern path/to/file_or_directory
```

Include hidden files and entries listed in .gitignore:

```
rg --hidden --no-ignore pattern
```

Only search the files whose names match the glob pattern(s) (e.g. README.*):

```
rg pattern --glob filename_glob_pattern
```

Recursively list filenames in the current directory that match a pattern:

```
rg --files | rg pattern
```

Only list matched files (useful when piping to other commands):

```
rg --files-with-matches pattern
```

Show lines that do not match the pattern:

```
rg --invert-match pattern
```

Search for a literal string pattern:

```
rg --fixed-strings -- string
```
