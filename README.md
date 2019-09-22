# README

**Node.js API Structure Guide for:**  a standard Node.js web API. Shows how to create an API that interacts with a database using all four CRUD operations (Create-Read-Update-Delete). Simulates a blog application with an articles collection. 

**Stack:** JavaScript/Node.js, Express web framework, and MongoDB NoSQL database.  

**Status:** Unfinished first draft. Not ready for use.

**Documentation:** https://www.techandstartup.com/guides/nodejs/api-structure

To use this app you need to have either a local or cloud version of MongoDB. 
Then change the .env-example file name to just .env, and make sure the MONGODB_URI constant is set to the right URI of your database. If you have a local MongoDB database named my_local_db running then it is set correctly.

Start a local MongoDB server from any window in your computer's terminal with the command:
mongod

To run the app in your development environment with debug mode:  
DEBUG=node-api-structure:* npm start

Or without Debug mode: 
npm start