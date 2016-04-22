#install
```
apt-get install mongodb
```
#start
```
mongod  --dbpath ~/db --auth --fork --logpath ~/db.log
```
```
mongo
use admin
>db.addUser(“root”, “root”)
```
