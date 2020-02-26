# 3. Building a Backend with MongoDB, Express, and Node
Skeleton application overview

Feature breakdown

Focus of this chapter – the backend

User model

API endpoints for user CRUD

Auth with JSON Web Tokens

How JWT works
Implementing the skeleton backend

Folder and file structure

Setting up the project

Initializing package.json

Development dependencies

Babel

Webpack

Nodemon

Config variables

Running scripts

Preparing the server

Configuring Express

Starting the server

Setting up Mongoose and connecting to MongoDB

Serving an HTML template at a root URL

User model

User schema definition

Name

Email

Created and updated timestamps

Hashed password and salt

Password for auth

As a virtual field

Encryption and authentication

Password field validation

Mongoose error handling

User CRUD API

User routes

User controller

Creating a new user

Listing all users

Loading a user by ID to read, update, or delete

Loading

Reading

Updating

Deleting

User auth and protected routes

Auth routes

Auth controller

Sign-in

Sign-out

Protecting routes with express-jwt

Requiring sign-in

Authorizing signed in users

Protecting user routes

Auth error handling for express-jwt

Checking the standalone backend

Creating a new user

Fetching the user list

Trying to fetch a single user

Signing in

Fetching a single user successfully

Summary
