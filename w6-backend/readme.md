# Backend Server

By the end of this lesson. You should be able to set up two separate servers that will speak with each other -- one with frontend code and the other with react code.

This repository contains the backend for the `w6-frontend` repository.

## Installation

1. Clone this repository

1. `cp nodemon.sample.json nodemon.json`

1. Create a new Cluster on [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) titled something like `general-purpose` or reuse one you already have.

1. Update the `MONGO_DB_CONNECTION` in your `nodemon.json` file with the full connection string. Make sure you include the password you set up for the database and change the name of the database from `test` to something lke `journal_dev`.

1. `npm install`

1. `npm run reset-db`

1. `npm run dev`

Once installation is working, take a look at the existing code to make sure you understand what is happening. Then, try making requests to the API.
