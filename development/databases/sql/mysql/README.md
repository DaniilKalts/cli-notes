### mariadb

**Usage:** The mariadb client tool. <br />
More information: https://mariadb.com/kb/en/mariadb-command-line-client/. <br />

Connect to a specific MariaDB database:

```
mariadb db_name
```

Connect to a specific MariaDB database using username and password:

```
mariadb --user user_name --password=your_password db_name
```

Connect to a specific MariaDB database using username, password and host:

```
mariadb --host specified_host --user user_name --password=your_password db_name
```

Connect to a specific MariaDB database using a custom defaults file:

```
mariadb --defaults-file=/path/to/my.cnf db_name
```
