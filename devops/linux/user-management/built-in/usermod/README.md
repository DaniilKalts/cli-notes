### usermod

**Usage:** Modify a user account. <br />
More information: https://manned.org/usermod. <br />

Change a username:

```
sudo usermod --login new_username username
```

Change a user ID:

```
sudo usermod --uid id username
```

Change a user shell:

```
sudo usermod --shell path/to/shell username
```

Add a user to supplementary groups (mind the lack of whitespace):

```
sudo usermod --append --groups group1,group2,... username
```

Remove a user from specific groups:

```
sudo usermod --remove --groups group1,group2,... username
```

Change a user home directory:

```
sudo usermod --move-home --home path/to/new_home username
```

Lock an account:

```
sudo usermod --lock username
```

Unlock an account:

```
sudo usermod --unlock username
```
