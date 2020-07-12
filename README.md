Run this:

```
mysql -u [user] -p[password] -h [host]
```

then ...

```
ALTER USER '[user]'@'[host]' IDENTIFIED WITH mysql_native_password BY '[password]';
```

where [user], [host] and password] are replaced by your actual credentials.
