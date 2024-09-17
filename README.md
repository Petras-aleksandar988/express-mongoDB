1. Create MongoDB connection.
2. Create .env file in the root directory and use the connection string to update the env variable, like in the .env-example file.
3. Run npm install to install all dependencies.
4. From the root directory, type npm run dev to start the server, load .env variables (--env-file=.env), and listen on port 8000 (or another available port on your local machine) with any changes (--watch, no need to install Postman).
5. From http://localhost:8000, there are three routes (/users, /posts, /comments), each with CRUD functionality
