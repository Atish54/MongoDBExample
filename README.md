# Introduction-to-NodeJS-Module3-Lab

#### Usage
```
node migrate-data.js <number of objects to process at once>
```

Examples: 

```
node migrate-data.js 200
```
The above will produce 5 paralel queries each with 200 objects. 

If program work as expected the output in console should be like this:

```
Open MongoDB connection
Inserting records 0/200 of 1000
Inserting records 200/400 of 1000
Inserting records 400/600 of 1000
Inserting records 600/800 of 1000
Inserting records 800/1000 of 1000
Pass 0: Inserted 200 records
Pass 1: Inserted 200 records
Pass 2: Inserted 200 records
Pass 3: Inserted 200 records
Pass 4: Inserted 200 records
Close MongoDB connection

```
