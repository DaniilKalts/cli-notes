### sed

**Usage:** GNU stream editor for filtering and transforming text. <br />
**More information:** https://www.gnu.org/software/sed/manual/sed.html. <br />

Replace apple with mango on all lines using basic regex, print to stdout:

```
command | sed 's/apple/mango/g'
```

Replace apple with APPLE on all lines using extended regex, print to stdout:

```
command | sed --regexp-extended 's/(apple)/\U\1/g'
```

Use basic regex to replace apple with mango and orange with lime in-place in a file (overwriting original file):

```
sed --in-place -e 's/apple/mango/g' -e 's/orange/lime/g' path/to/file
```

Execute a specific sed script file and print the result to stdout:

```
command | sed --file path/to/script.sed
```

[p]rint only the first line to stdout:

```
command | sed --quiet '1p'
```

[d]elete lines 1 to 5 of a file and back up the original file with a .orig extension:

```
sed --in-place=.orig '1,5d' path/to/file
```

[i]nsert a new line at the beginning of a file, overwriting the original file in-place:

```
sed --in-place '1i\your new line text\' path/to/file
```

Delete blank lines (with or without spaces/tabs) from a file, overwriting the original file in-place:

```
sed --in-place '/^[[:space:]]*$/d' path/to/file
```
