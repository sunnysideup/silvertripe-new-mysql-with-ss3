Run this:

```
mysql -u [user] -p[password] -h [host]
```

then ...

```
ALTER USER '[user]'@'[host]' IDENTIFIED WITH mysql_native_password BY '[password]';
```

where [user], [host] and password] are replaced by your actual credentials.

# new user

```
CREATE USER 'a'@'localhost' IDENTIFIED WITH mysql_native_password BY 'b';
GRANT ALL PRIVILEGES ON [database].* TO 'a'@'localhost' WITH GRANT OPTION;
```
source: https://linuxize.com/post/how-to-create-mysql-user-accounts-and-grant-privileges/
