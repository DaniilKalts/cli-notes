### uniq

**Usage:** Output the unique lines from a input or file.
Since it does not detect repeated lines unless they are adjacent, we need to sort them first. <br />
**More information:** https://www.gnu.org/software/coreutils/manual/html_node/uniq-invocation.html. <br />

Display each line once:

```
sort path/to/file | uniq
```

Display only unique lines:

```
sort path/to/file | uniq --unique
```

Display only duplicate lines:

```
sort path/to/file | uniq --repeated
```

Display number of occurrences of each line along with that line:

```
sort path/to/file | uniq --count
```

Display number of occurrences of each line, sorted by the most frequent:

```
sort path/to/file | uniq --count | sort --numeric-sort --reverse
```
