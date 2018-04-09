# Back End Journey

* Build a RESTful API using Express and Node.js.
* **Persist API Data to a Database. (this week)**
* Secure an API.
* Test, Package and Deploy an API.
* Full Stack Project.

## Thanks for the Feedback!

* breaks too long, move to 5 mins instead of 10.
* training kit, work in progress. Notes will be fleshed out there.
* offer students as tribute when no-one heeds the call during to be navigator during lecture.
* too much new information. The firehose effect.
* readmes not clear enough. Heard! we'll revisit al readmes.
* more VSCode/chrome tools tricks please! stay alert, they're sprinkled throughout the lectures, think: _lecture easter eggs_. Seriously, it's something we're putting together **recommended tooling and setup**.

## Day 1

* verify mongo installation.
* verify mongo is running (don't stop it until you're done working with it).
* quick intro to databases.
* what is NoSQL and what are document databases.
* why MongoDB.
* working with local instance of MongoDB. DBAAS options.
* a BRIEF look at the _mongo shell_.
* connecting to mongo from our API.
* why mongoose? what is it? benefits and drawbacks.
* introduce mongoose Schemas ad Models.
* define a basic document Schema.
* creating documents using mongoose.
* querying all documents using mongoose.
* querying one document by id using mongoose.

That looks like a lot, but, it's not, I promise!

Client <--> [API (driver = translate from js objects to BSON)] <--> DB Server

DBMS === Management System.

Database = pile of information, organized, easy to retrieve.

Relational DB = RDBMS, uses a query language called Structured Query Language (SQL).

RDBMS thinks in sets.

Applications work with objects (or classes).

NoSQL = Not Only SQL (key-value pairs, document, graph).

* more natural way of structuring data.

Document Databases (MongoDB)

* data stored as BSON (Binary JSON).
* inside the application it's POJO (Plain Old JS Object).

Why MongoDB

* popular.
* mature over 10 years.
* JS end to end.
* dynamic shemas.

We'll use mongoose to connect.

* schemas.
* query builder.
* middleware (lifecycle hooks).
* schema validation.

How.

* define schema (template).
* create a model by compiling a schema.
* an instance of a model is a mongoose document.
* a mongoose documents represents a db document.
* we use mongoose documents to act on data on the db.

MongoDB Server

* databases
  * collections
    * documents
      * fields
