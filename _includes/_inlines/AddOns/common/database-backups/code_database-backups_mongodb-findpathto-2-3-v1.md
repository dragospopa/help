<!-- usedin: [ _includes/_inlines/AddOns/common/database-backups/database-backups_mongodb-v1.md] -->

```

$ find /path/to/unarchived/folder '(' -name 'MongoDB.tar' -o -name 'Mongo*.tar.gz' ')' -type f -exec basename {} ';'    

```