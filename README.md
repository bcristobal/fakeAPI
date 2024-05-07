# FakeAPI with json-server

This repository contains a basic implementation of a FakeAPI using json-server in JavaScript. This tool allows you to quickly create a RESTful API using a JSON file as a database.


## Usage

You can click [here](https://my-json-server.typicode.com/bcristobal/fakeAPI) to make a call to the API.

## Run Locally

First, you need to install the json-server package:

    npm install json-server

Then, you can run using the next command:

    npx json-server --watch db.json --port 3333

Use the '-- port' to specify the number of the port and '--watch' tells the server to monitor the db.json file for any changes. If any changes are detected in the db.json file, the server will automatically reload the data without needing to be manually restarted. 



