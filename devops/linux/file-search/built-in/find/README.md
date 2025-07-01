Find files by extension.

```
find root_path -name '*.ext'
```

Find files in case-insensitive mode.

```
find root_path -iname '*.ext'
```

Find directories matching a given name, in casae-insensitive mode.

```
find root_path -type d -iname '*substring*'
```

Find files matching a given pattern, excluding specific paths.

```
find root_path -name '*.ext' -not -path 'path/to/directory'
```

Find files matching a given size range, limiting the recursive depth to "n".

```
find root_path -maxdepth n -size +500k -size -10M
```

Find files that modified in the last n minutes.

```
find root_path -mmin n
```
