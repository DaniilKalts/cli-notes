### htop

**Usage:** Display dynamic real-time information about running processes. An enhanced version of `top`. <br />
More information: https://htop.dev/. <br />

Start htop:

```
htop
```

Start htop displaying processes owned by a specific user:

```
htop --user username
```

Display processes hierarchically in a tree view to show the parent-child relationships:

```
htop --tree
```

Sort processes by a specified sort_item (use htop --sort help for available options):

```
htop --sort sort_item
```

Start htop with the specified delay between updates, in tenths of a second (i.e. 50 = 5 seconds):

```
htop --delay 50
```

See interactive commands while running htop:

```
<?>
```

Switch to a different tab:

```
<Tab>
```

Display help:

```
htop --help
```
