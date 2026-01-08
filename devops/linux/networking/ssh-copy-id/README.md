### ssh-copy-id

**Description:** Install your public key in a remote machine's authorized_keys. <br />
**More information:** https://manned.org/ssh-copy-id. <br />

Copy your keys to the remote machine:

```
ssh-copy-id username@remote_host
```

Copy the given public key to the remote:

```
ssh-copy-id -i path/to/certificate username@remote_host
```

Copy the given public key to the remote with specific port:

```
ssh-copy-id -i path/to/certificate -p port username@remote_host
```
