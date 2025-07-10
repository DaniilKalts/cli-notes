### docker system

**Usage:** Manage Docker data and display system-wide information. <br />

Display help:

```
docker system
```

Show Docker disk usage (df - disk free):

```
docker system df
```

Show detailed information on disk usage:

```
docker system df --verbose
```

Remove unused data (append --volumes to remove unused volumes as well):

```
docker system prune
```

Display system-wide information:

```
docker system info
```
