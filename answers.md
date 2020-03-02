1. What is responsible for defining the routes of the `games` resource?

The create_router.js file in the server file folder.

2. What do you notice about the folder structure?  Whats the client responsible for? Whats the server responsible for?

The client folder is responsible for the front-end code part while the server is responsible for the back-end code of the app.

3. What are the the responsibilities of server.js?
It includes the server code.

4. What are the responsibilities of the `gamesRouter`?

It gets the end points to the API using  '/api/games'

5. What process does the the client (front-end) use to communicate with the server?

Through the post request form and through fetching data

6. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs

This is a callback function to get back the baseURl in the post and then string, as when exchanging data between a browser and a server, the data can only be text

7. Which of the games API routes does the front-end application consume (i.e. make requests to)?

The RESTful routes are get,post,delete

8. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?

For the management CRUD functions

## Extension

Why do we need to use [`ObjectId`](https://mongodb.github.io/node-mongodb-native/api-bson-generated/objectid.html) from the MongoDB driver?

Add to your diagram the dataflow for removing a game.
