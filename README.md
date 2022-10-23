# url-shortener
The application is the backend of a basic url-shortener.

Should we talk about the functioning of a basic url-shortener a bit?
If you would see in the mongo model you will see that the schema contains 5 fields.
We are generating a urlId for the given original url and storing it in the database.
When we make a GET request to the short-url it searches in the database and returns the original url. 
Simple!!!

To import dependencies using the "import" statement add "type":"module" at the end in the package.json file.

The dependencies we will be using:

    -dotenv: this package loads the environment variables from a file called .env to process.env
    -Express.js: this is a minimal and flexible web application framework for Node.js
    -Mongoose: this is a MongoDB object modeling tool for Node.js
    -NanoID: This package enables us to generate the short IDs for our URLs


    
