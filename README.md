# basic-crud-operations-on-db
- db.movie.find() : Show all the documents in collection movie
- db.movie.find().limit(10) : Print only 10 documentss of the database
- db.movie.find().sort({budget : 1}).limit(10) : Finding bottom movies by budget
-  db.movie.find().sort({budget : -1}).limit(10) : Finding top movies by budget
-  db.movie.find({$and : [ { budget : {$gt : 9000 } }, { budget : {$lt : 9600 } }   ]  }) : Finding all the movies which has budget greater than 9000 and less than 9600n and print them

