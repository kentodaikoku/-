# Mysql

## log

```
cat /var/log/mysqld.log
```

## backup



## sql

### 権限

```
ユーザー作成
mysql> GRANT ALL PRIVILEGES ON *.* TO ユーザー名@localhost IDENTIFIED BY 'パスワード' WITH GRANT OPTION;
mysql> FLUSH PRIVILEGES;

権限確認
mysql> SHOW GRANTS FOR ユーザ名@localhost \G
```


### 操作

```
- DB作成
create database [database_name];
```

