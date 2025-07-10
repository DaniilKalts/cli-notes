### userdel

**Usage:** Remove a user account or remove a user from a group. <br />
More information: https://manned.org/userdel. <br />

Remove a user:

```
sudo userdel username
```

Remove a user in other root directory:

```
sudo userdel --root path/to/other/root username
```

Remove a user along with the home directory and mail spool:

```
sudo userdel --remove username
```
