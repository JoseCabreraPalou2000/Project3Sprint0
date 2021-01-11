## What is MongoDB

MongoDb is a document-oriented database. This means that instead of saving the data in records, you save the data in documents.

## How does it work

MongoDB is written in C ++, although the queries are made by passing JSON objects as a parameter. This is quite logical, since the documents themselves are stored in BSON. For example:

db.Clientes.find ({Name: "Pedro"});

