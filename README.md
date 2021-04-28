# 


MongoDB is web scale. (Google it. Trigger warning: highly _offensive_.) For this
assignment, we will be using a restaurants file that is comprised of various
documents. In this exercise, you will use the open-source MongoDB NoSQL
Database to write queries. Practice makes perfect, yo!

Before we begin, just a quick refresher on NoSQL databases. MongoDB, Cassandra,
CouchBase, Redis, and many others are examples of NoSQL databases. Each
database is useful depending on how the data is being stored. The four main
types of NoSQL databases are: (1) key-value stores, (2) Column-oriented
databases, (3) Document-oriented, (4) Graph databases.

One of the main benefits of using MongoDB is that it avoids the rigidity of
table-based relational databases and instead opts for JSON-like documents
that allow for dynamic schemas. You can stick whatever you want in there:
YOLO woot! But, it comes at a cost, you don't get many of the guarantees
that a relational database gives you.

You can connect to the database as follows, if you're using the mongodb
command line client

```
mongo "mongodb+srv://mgt858.zbst3.mongodb.net/restaurants" --username <username>
```

Obviously, replace `<username>` with your username.
You'll need to be on the Yale VPN to connect. The username and password are
in your "Dashboard" on the class website. Everybody has the same username and
password for this assignment.

Alternatively, if you want a GUI, you might like [MongoDB Compass](https://www.mongodb.com/products/compass).

You'll want to read the [MongoDB manual](https://docs.mongodb.com/manual/tutorial/query-documents/) to
learn how to write queries. It's a JavaScript-like language.

One last thing: when you are working with MongoDB through the shell, you may
find your eyes trying to sort through unreadable and jumbled data. We fix this
by using a .pretty() command format after our queries. For example, we can do
something like db.users.find() but that would give us data that looks like this:

  ```
  { "_id" : ObjectId("5c7997e7ad685885625abce3"), "userId" : 1, "name" : "Al" }
  { "_id" : ObjectId("5c7997e7ad685885625abce4"), "userId" : 2, "name" : "Betty" }
  { "_id" : ObjectId("5c7997e7ad685885625abce5"), "userId" : 3, "name" : "Cameron" }

  ```

  To fix this, we can instead have the query read db.users.find().pretty() which
  would result in the data looking like this:

  ```
  {
      "_id" : ObjectId("5c7997e7ad685885625abce3"),
      "userId" : 1,
      "name" : "Al"
  }
  {
      "_id" : ObjectId("5c7997e7ad685885625abce4"),
      "userId" : 2,
      "name" : "Betty"
  }
  {
      "_id" : ObjectId("5c7997e7ad685885625abce5"),
      "userId" : 3,
      "name" : "Cameron"
  }

  ```
  Much better on the eyes! Rather than type .pretty() after each query we write,
  we can just make this the default option.

  Before starting, make sure you add this to the beginning of your file!

    DBQuery.prototype._prettyShell = true



## Suggested order

We suggest you complete the questions in the following order

- [ ] 00-viewing-all-documents
- [ ] 01-searching-cuisine-name-borough
- [ ] 02-removing-id
- [ ] 03-queens
- [ ] 04-10-restaurants
- [ ] 05-date-night
- [ ] 06-date-night-greater-than-85
- [ ] 07-date-night-not-american
- [ ] 08-ascending-order
- [ ] 09-wil
- [ ] 10-ces
- [ ] 11-friday-night
- [ ] 12-friday-night-cant-decide
- [ ] 13-power-outage
- [ ] 14-advanced-db


As you complete questions, you can mark them as complete
in this Markdown file,  but you don't have to do so.
See [this example](https://github.blog/2014-04-28-task-lists-in-all-markdown-documents/).

