# SQL

> What is the difference between a primary key and a foreign key

A primary key is the items key that identifies it, a foreign key links the item to another item, where the foreign key is that items
primary key.

> What is an Alias?

It is how you can call a table by another name in SQL by putting the new name next to the table name.

> Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

SELECT p.*, d.* FROM doctors d JOIN patients p ON d.patientId = p.id

[Job Bidding](https://github.com/ConnorH14/job-bid)