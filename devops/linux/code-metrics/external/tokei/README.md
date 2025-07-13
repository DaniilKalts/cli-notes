### tokei

**Usage:** Display statistics about code. <br />
More information: https://github.com/XAMPPRocky/tokei. <br />

Display a report for the code in a directory and all subdirectories:

```
tokei path/to/directory
```

Display the report for the code in a directory and all subdirectories (verbose progress):

```
tokei path/to/directory --verbose
```

Display a sorted report for the code in a directory and all subdirectories:
- code
- files
- comments
- blanks
- total

```
tokei path/to/directory --sort choice
```

Display a report for the code in a directory and all subdirectories in JSON format:

```
tokei path/to/directory --output json
```

Display a report for a directory excluding .min.js files:

```
tokei path/to/directory --exclude *.min.js
```

Display statistics for individual files in a directory:

```
tokei path/to/directory --files
```

Display a report for all files of type Rust and Markdown:

```
tokei path/to/directory --type Rust,Markdown
```
