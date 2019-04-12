# sql
Easy SQL via the cli


## SQL Cli that get's out of your way

```shell
sql "SELECT * FROM localhost:database.table WHERE 1 = 1;"
```

## If you have access, it has access

```shell
LOCAl=localhost/database.table 
REMOTE=host.com:3306/database.table

sql "SELECT * FROM $LOCAl AS local JOIN $REMOTE AS remote ON local.id = remote.id;"
```
