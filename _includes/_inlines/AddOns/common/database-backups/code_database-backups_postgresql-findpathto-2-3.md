<!-- layout:code post: database-backups_postgresql -->

```

$ find /path/to/unarchived/folder '(' -name '*.sql' -o -name '*.sql.gz' ')' -type f -exec basename {} ';'    

```