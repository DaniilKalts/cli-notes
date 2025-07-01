##### List all NetworkManager connections (shows name, UUID, type and device):

```
nmcli connection
```

##### List only active NetworkManager connections (shows name, UUID, type and device):

```
nmcli connection --active
```

##### Activate a connection:

```
nmcli connection up uuid uuid
```

##### Deactivate a connection:

```
nmcli connection down uuid uuid
```

##### Show connection details (including secrets)

```
nmcli --show-secrets connection show "wifi"
```

##### Get the password from a connection

```
sudo nmcli --show-secrets --get-values 802-11-wireless-security.psk connection show "wifi"
```

##### Show connection configuration file

```
sudo bat /etc/NetworkManager/system-connections/wifi.nmconnection
```

##### Print the password and QR code for the current Wi-Fi network:

```
nmcli device wifi show-password
```

##### Print the statuses of all network interfaces:

```
nmcli device status
```

##### Print the available Wi-Fi access points:

```
nmcli device wifi
```
