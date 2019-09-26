Run a single mongo db instance but with it configured as a replica set. This will enable the database with an "Oplog", the existance of the oplog will allow the use of database "transactions".

	>>> docker-compose up