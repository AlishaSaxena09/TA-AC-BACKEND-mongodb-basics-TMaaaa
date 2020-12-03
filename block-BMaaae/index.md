writeCode

Write code to:-

- create a database named `sports`.

// use sports

- list all databases present in local mongod server.

// show dbs

- create 3 collections named `cricket`, `football`, `TT` in sports databse.

// db.collection.insert({'name':'cricket','name': 'football','name': 'TT'})

- add multiple players in those collections which should have fields like `name`, `age` and `email` and `bid_price`.

// db collection ('football');
// db collection ('cricket');
// db collection ('TT');

- list all collections in sports database.

// show collections

- rename `TT` collection to `tennis`.

// db.TT.renameCollection('Tennis')

- create a capped collection called `khokho` which should have max 3 documents.
  Try inserting more than 3 and see what happens?
- check whether a collection is capped or not?
- drop all documents from `football` collection.
- delete cricket collection completely.
- delete sports database.
- check which database you are connected to ?
- connect to test database
