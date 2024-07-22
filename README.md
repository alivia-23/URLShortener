# URL Shortener (Backednd)

Design and develop the backend of URL shortener service that takes in a valid URL and returns a shortened URL, redirecting the user to the previously provided URL

Also keep track of total visits/clicks on the URL

### Routes

* **POST/URL** - Generates a new short URL and returns the shortened URL in the format example.com/random-id
* **GET/:id** - Redirects the user to the original URL
* **GET/URL/analytics/:id** - Returns the clicks for the provided short id

## Technologies Used
  * Used **shortid** library of npm to generate short id of the given urls
  * Used **MongoDB** to store and track urls data
  * Used **Express** as a middleware to parse incoming bodies
  * Used **Postman** for REST API routes call and check status

## Steps to start the project
  * **npm install** should install all the dependencies of this project
  * **npm start** runs the index.js file
  * open a new terminal and type **mongosh** to start connecting the MongoDB database
  * Enter Command **show dbs** lists the number of database created
  * Then **show collections** -> urls
  * Next **db.urls.find({})** -> It will be blank first but after creating the shortId and redirectURL it shows list of urls as object
  * download **postman** locally to get access to REST API calls for the local project otherwise if you use web version of postman it will show error


     


