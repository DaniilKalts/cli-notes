### passwd

Change a user's password. <br />
More information: https://manned.org/passwd. <br />

Change the password of the current user interactively:

```
passwd
```

Change the password of a specific user:

```
passwd username
```

Get the current status of the user:

```
passwd --status
```

Make the password of the account blank (it will set the named account passwordless):

```
passwd --delete
```

Set password programmatically (ideal for install scripts):

```
yes password | passwd
```
