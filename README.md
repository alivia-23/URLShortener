# URL Shortener

Design a URL shortener service that takes in a valid URL and returns a shortened URL, redirecting the user to the previously provided URL

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


## Open new terminal for MongoDB connection commands
  * show dbs -> lists the number od databased created
  * show collections -> urls
  * db.urls.find({}) -> It will be blank first but after creating the shortId and redirectURL it shows list of urls as object

     


