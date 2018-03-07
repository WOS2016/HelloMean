# MongoDB 3.6.3 Community "MongoDb Compass Community" is great client side tools, which is installed with MongoDb together!

## Use DaaS on mlab.com (https://mlab.com/)

## Download & Install MongoDB on local.

# Use MongoDB on local.
## Server Side
- Create default MongoDB on local
  >md \data\db

- Go to MongoDB default folder:
  >cd C:\Program Files\MongoDB\Server\3.6\bin

- run MongoDB server 
  >C:\Program Files\MongoDB\Server\3.6\bin\mongod.exe

[initandlisten] exception in initAndListen: NonExistentPath: Data directory C:\data\db\ not found., terminating

## Client Side
- Goto MongoDB default folder
    >cd C:\Program Files\MongoDB\Server\3.6\bin
- Run mongo.exe to enter MongoDb Client shell (Command Line)
    > C:\Program Files\MongoDB\Server\3.6\bin\mongo.exe
    >mongo.exe reviewking

- listing some of commands:
    >db.adminCommand('listDatabases')
    >show dbs
    >db.dropDatabase();
- Create a DB
    > use helloMongoDB;
    > s = { Name : "John Doe" }
    > db.helloCollection.insert( s );			===> collection called testData

- view DB
    >show dbs
- use DB
    >use helloMongoDB
- view collection


## Backup Local MongoDB

## Restore Local MongoDB

