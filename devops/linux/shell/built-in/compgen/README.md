### compgen

**Usage:** A built-in command for auto-completion in Bash, which is called on pressing `Tab` key twice. <br />
More information: https://www.gnu.org/software/bash/manual/bash.html#index-compgen. <br />

List all commands that you could run:

```
compgen -c
```

List all commands that you could run that start with a specified string:

```
compgen -c str
```

List all aliases:

```
compgen -a
```

List all functions that you could run:

```
compgen -A function
```

Show shell reserved keywords:

```
compgen -k
```

See all available commands/aliases starting with 'ls':

```
compgen -ac ls
```

List all users on the system:

```
compgen -u
```

Display help:

```
compgen --help
```
