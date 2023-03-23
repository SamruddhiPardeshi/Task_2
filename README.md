# Task_2


# PROFESSIONAL PORTFOLIO
TASK-2                                                        
Task2 is all about :                      
a. Designing schema for database.
b.Starting MongoDB local server and pointing to backend.
c.Defing routes for backend.  
d.Adding authenticaition middleware.

1. DESIGN SCHEMA FOR PROFESSIONAL PORTFOLIO:
To design a schema for a Professional Portfolio , you will need to ﬁrst identify the types of data that you want to store in your database. Here's a possible schema that could be used:

1.	User collection: This collection will store the user data, such as the username, email, and password.

2.	Project collection: This collection will store information about the projects that the user has worked
on or completed.

3.	Skill collection: This collection will store the skills that the user possesses.

4.	Experience collection: This collection will store the work experience of the user.

5.	Education collection: This collection will store the educational qualiﬁcations of the user.



Start mongodb local server and point the backend to the server:

To start a MongoDB local server, follow these steps:
1.	Create a MongoDB Cloud account.
2.	Create a new folder for your MongoDB data ﬁles.
3.	Open a terminal or command prompt and navigate to the MongoDB bin directory.
4.	Run the command "mongod --dbpath /path/to/data/folder" to start the MongoDB server.

Once the local server is up and running, you can connect your backend to it. The speciﬁc steps will depend
on the programming language and framework you're using for your backend. However, the general process
is as follows:

1.	Install the MongoDB driver for your chosen programming language.
2.	In your backend code, create a new connection to the MongoDB server using the driver's connection
string or conﬁguration options.
3.	Once you have established a connection to the MongoDB server, you can perform CRUD (create, read,
update, delete) operations on your database through the driver's API.

MongoDB CRUD Operations:

 Create Operations:
Create or insert operations add new documents to a collection. If the collection does not currently exist, insert operations will create the collection.

MongoDB provides the following methods to insert documents into a collection:

db.collection.insertOne() New in version 3.2

db.collection.insertMany() New in version 3.2

Read Operations:
Read operations retrieve documents from a collection; i.e. query a collection for documents. MongoDB provides the following methods to read documents from a collection:

db.collection.find()

You can specify query filters or criteria that identify the documents to return.

Update Operations:
Update operations modify existing documents in a collection. MongoDB provides the following methods to update documents of a collection:

db.collection.updateOne() New in version 3.2

db.collection.updateMany() New in version 3.2

db.collection.replaceOne() New in version 3.2

In MongoDB, update operations target a single collection. All write operations in MongoDB are atomic on the level of a single document.

Delete Operations:
Delete operations remove documents from a collection. MongoDB provides the following methods to delete documents of a collection:

db.collection.deleteOne() New in version 3.2

db.collection.deleteMany() New in version 3.2

In MongoDB, delete operations target a single collection. All write operations in MongoDB are atomic on the level of a single document.

You can specify criteria, or filters, that identify the documents to remove. These filters use the same syntax as read operations.

Deﬁne all the routes of the	backend:
Deﬁning routes in a backend application depends on the speciﬁc framework or library used, as application functional
ity and requirements.

Add authentication middleware:
Adding authentication middleware to a backend application can help ensure that only authorized users can access certain routes or perform certain actions.


















