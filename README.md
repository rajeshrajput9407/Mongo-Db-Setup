# Mongo-Db-Setup
Mongo Db Database restore and Dump Database


Install mongodb 4.0 and install
Install Mongo Compass

You have to create Two folder 
1.dump in bin folder

C:\Program Files\MongoDB\Server\4.0 create data folder with the name 
2.data


Dump from Old  Database 
cd C:\Program Files\MongoDB\Server\4.0\bin  commandProm With Administrator mode 

mongodump --db webmine-CRF
webmine-CRF(Original DB)



Restore the Database: CMD USing Administrator mode
cd C:\Program Files\MongoDB\Server\4.0\bin


mongorestore --db webmine-CRF dump/webmine-CRF

webmine-CRF(New DB Name For Dumping)
dump/webmine-CRF (Original Db)
