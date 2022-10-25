# Django Rest Framework

**A REST API** is standardized way to provide data to other applications. Those applications can then use the data however they want. Sometimes, APIs also offer a way for other applications to make changes to the data.

_There are a few key options for a REST API request:_

1. GET - The most common option, return some data from the API based on the endpoint you visit and any parameters you provide.

2. POST - Creates a new record that gets appended to the database

3. PUT - Looks for a record at the give URI you provide. If it exists, update the existing record. If not, create a new record.

4. DELETE - Deletes the record at the given URI.

5. PATCH - Update individual fields of a record.

Typically, an API is a window into a database. The API backend handles the querying the database and formatting the response. What you recieve is a static response, usually in JSON format, of whatever resource you requested.

REST APIs are so commonplace in software development, it's an essential skill for a developer to know how they work. **APIs are how applications communicate with one another or even within themselves**

For example, in web development many applications rely on REST APIs to allow the front end to talk to the back end.

The process of querying and converting tabular database values into JSON or another format is called **serialization**. When you're creating an API, correct serialization of data is the major challenge. 
