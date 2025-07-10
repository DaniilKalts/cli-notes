### su

Switch shell to another user. <br />
More information: https://manned.org/su. <br />

Switch to superuser (requires the root password):

```
su
```

Switch to a given user (requires the user's password):

```
su username
```

Switch to a given user and simulate a full login shell:

```
su - username
```

Execute a command as another user:

```
su - username --command "command"
```
