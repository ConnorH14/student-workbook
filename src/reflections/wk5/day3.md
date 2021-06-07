# More MongoDB

> In simple terms what is a sub-document?

A sub-document is a document nested in another document.

> When might you use a sub-document?

Sub-documents are useful when you have a lot of smaller bits of data that need to all be stored as one big slice of data.

> How do you add to a collection of sub-documents? What about editing them?

You can pass an entire object containing the sub-documents into the database, and to edit them you can use the findOne method.

> [Galaxy Server](https://github.com/ConnorH14/galaxy-server)