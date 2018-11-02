# REST JavaScript tutorial 
REST and JavaScript

# Installation
1. Create a project using <code>npm init</code>
2. Now install JSON server  using <code>npm install json-server --save-dev</code>
3. Add an alias script to the <code>package.json</code> file, 
  <code>
    "scripts": {
      "devdb": "json-server --watch src/datarepo/db.json"
    }
  </code>
  
4. To start the JSON server execute <code>npm run devdb</code> from the command prompt

# Alternatively clone and run the project
1. Clone the project
2. Run <code>npm install</code> from the project folder to install the dependencies
3. To start the JSON server execute <code>npm run devdb</code> from the command prompt

# Querying the json resource
1. On running the command <code>npm run devdb</code> the terminal will print out the endpoint url
2. Open the endpoint URL using a browser or postman, e.g. <code>http://localhost:3000/tools </code>
3. You're now all set to consume the data via your frontend website