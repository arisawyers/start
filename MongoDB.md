# MongoDB

https://www.mongodb.org/

## Bash Shortcuts

### Start `mongod` in User Directory with Command `mgd`

```bash
# MongoD in User Directory (`~/mongo`)

mgd() {
  mkdir -p ~/mongo/data/db/
  mkdir -p ~/mongo/data/logs/
  touch ~/mongo/data/logs/mongo.log
  mongod --dbpath ~/mongo/data/db/ --logpath ~/mongo/data/logs/mongo.log --fork
}
```
