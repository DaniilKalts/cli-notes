### psql

**Usage:** PostgreSQL client. <br />
More information: https://www.postgresql.org/docs/current/app-psql.html. <br />

Connect to the database. By default, it connects to the local socket using port 5432 with the currently logged in user:

```
psql database
```

Connect to the database on given server host running on given port with given username, without a password prompt:

```
psql --host host --port port --username username database
```

Connect to the database; user will be prompted for password:

```
psql --host host --port port --username username --password database
```

Execute a single SQL query or PostgreSQL command on the given database (useful in shell scripts):

```
psql --command 'query' database
```

Execute commands from a file on the given database:

```
psql database --file file.sql
```
