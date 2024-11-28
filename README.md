link to lesson:

https://www.codecademy.com/paths/create-a-back-end-app-with-javascript/tracks/back-end-development-capstones/modules/bapi-capstones-solution-code-and-next-steps/informationals/back-end-web-development-next-steps


# Back-End Web Development Next Steps

**Congratulations! Find some next steps to continue back-end development.**

Congratulations on all your work building APIs and learning about back-end web development! If you want to take your skills to the next level or expand your applications, below are some additional resources. These resources are intended to get you started, but you will likely need to consult additional documentation and the internet to implement them in your apps.

# Deployment
Deployment means actually getting your application running on the web and accessible to all! Many deployment platforms provide a free pricing tier with some restrictions which is ideal for testing out applications, sharing with friends, or adding to a portfolio. After setting up your app on a free plan, if you end up wanting to be able to support faster performance or high traffic to your app, there are usually easy ways to upgrade your service without starting from scratch.

- Now is a lightweight service for deploying applications, particularly Node apps. Its a fast and free way to get applications on the web.
- Heroku is another popular cloud-hosting deployment service with support for Node.js and various database types. Heroku manages application deployment with Git, so take our Learn Git course if you are unfamiliar with it.

##### Note: SQLite with deployed apps

SQLite is a very quick and easy way to set up a database, but because the database lives in a single file, it is not always supported in cloud hosting. There are many other database types such as PostgreSQL and MySQL which have Node.js clients and can be used in deployed applications. These are just different dialects of SQL, and the syntax of PostgreSQL and MySQL is extremely similar to what you already know.

# SQLite and Databases
- node-sqlite, a Node-SQLite library built around the sqlite3 package that you already know. node-sqlite supports modern JavaScript interfaces such as ES6 Promises and async/await.

- Promises and asynch/await are powerful tools in JavaScript for handling slow steps in your code (such as database queries) without blocking other operations that should continue, and registering other actions that should be taken right when the slow steps complete. You began thinking about code running in parallel vs serially with node-sqlite3’s db.serialize(), but there are many other options to explore. Handling concurrency is one of the major challenges in optimizing API design.
- The SQLite Documentation is a great resource if you want to add more database functionality to your applications.
#### Object-Relational Mapping Tools (ORMs)

ORMs work as an interface between databases and your programs/servers. They often provide helper functions to handle common SQL tasks, so that you don’t have to write SQL queries directly in your JavaScript code. They can also ease the difficulties of working with multiple tables in a database. Two common JavaScript ORMs that support SQLite are Bookshelf.js and Sequelize.js, and you can use many other kinds of database with them as well.

# Authentication

Authentication, or confirming that a user is who they say they are, is an important part of a functional API—you probably don’t want just anybody to be able to read and write to your database! There are many options to assist with authenticating users and performing login/logout operations in your server. Passport is a widely-used middleware package for authentication in Node/Express servers.

