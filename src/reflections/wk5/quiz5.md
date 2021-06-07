# Intro to Server side concerns with JavaScript

**1.** What do the letters of the acronym `CRUD` stand for?

Create, Read, Update, Delete

**2.** Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

Post, Get, Put, and Delete

**3.** What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

It stands for Object relational mapper, and we use Mongoose as our ORM.

**4.** Which two `HTTP` request types include a body?

Put and Post

**5.** In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

callback, async

**6.** Fill in the missing piece of this snippet of code.
```js
import ______ from "_______"
let Schema = ________.Schema;
```
mongoose, mongoose, mongoose

**7.** What is middleware?

It is the code that runs between you and the database when you want to interact with a database. 

**8.** The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

request, response

**9.** 
Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

?tag=winter