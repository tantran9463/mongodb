# MongoCommand
## Export
## Import
## Restore
**Retore multiFileBson**

```
mongorestore --host hostname --port port --username username --password password --authenticationDatabase=admin -d dbname --nsInclude 'prefixfile*' directory
```

**Retore FileBson**
```
mongorestore --host hostname --port port --username username --password password --authenticationDatabase=admin -d dbname path/file.bson
```

