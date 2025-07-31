### cut

**Usage:** Cut out fields from `stdin` or files. <br />
**More information:** https://www.gnu.org/software/coreutils/manual/html_node/cut-invocation.html. <br />

Print a specific [c]haracter/[f]ield range of each line:

```
command | cut --characters|fields 1|1,10|1-10|1-|-10
```

Print a field range of each line with a specific delimiter:

```
command | cut --delimiter "delimiter" --fields 1|1,10|1-10|1-|-10
```

Print a character range of each line of the specific file:

```
cut --characters 1 path/to/file
```

Print specific fields of NUL terminated lines (e.g. as in find . -print0) instead of newlines:

```
command | cut --zero-terminated --fields 1
```
