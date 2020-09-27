### CMD scripts run chatapp and to attain chatlogs ###

# Connect to mongodb local server #
> npm start (BASH)
> open index.html on two instances
> Chat
> "C:\Program Files\MongoDB\Server\4.4\bin\mongo.exe" (CMD)

# Export to external json/csv file #
> change drive in CMD if not on your mongoexport.exe drive
* (So hade to execute command "d:" to change to D:\ 
> cd D:\MongoDB\mongodb-database-tools-windows-x86_64-100.1.1\bin\
> mongoexport --collection=chat --db=mongochat --out=D:\MongoDB\chatApplication\chatApplicationUsingMongoDB\ChatLogs\chatlog1.csv


** Please change directories acoording to your needs **