# Full-Stack React Projects

### Descripción del libro

Libere el poder del stack MERN construyendo diversas aplicaciones web usando React, Node.js, Express y MongoDB

#### Sobre este libro

* Cree aplicaciones web dinámicas con el stack MERN
* Aproveche el poder de React en la construcción de interfaces de usuario interactivas y complejas
* Desbloquee el potencial de Node, Express y MongoDB para crear aplicaciones modernas full-stack

#### Para quien es este libro

Full-Stack React Web Development Projects es para desarrolladores de JavaScript que tienen algo de experiencia con React, pero no tienen experiencia previa con el desarrollo full-stack que involucra a Node, Express y MongoDB, y que desean pautas prácticas para comenzar a construir diferentes tipos de web del mundo real aplicaciones con este stack.

#### Lo que vas a aprender

* Configure su entorno de desarrollo y desarrolle una aplicación MERN

* Implemente la autenticación y autorización de usuarios utilizando **JSON Web Tokens**

* Cree una aplicación de redes sociales ampliando la aplicación MERN básica

* Cree una aplicación online marketplace con carrito de compras y pagos **Stripe**

* Desarrolle una aplicación media streaming usando **MongoDB GridFS**

* Implemente server-side rendering con datos para mejorar el SEO

* Configure y use React 360 para desarrollar interfaces de usuario con capacidades de realidad virtual

* Aprenda las mejores prácticas de la industria para hacer que las aplicaciones del stack MERN sean confiables y escalables

#### En detalle

Los beneficios de usar full JavaScript stack para el desarrollo web son innegables, especialmente cuando se encuentran disponibles tecnologías robustas y ampliamente adoptadas, como React, Node y Express. La combinación de la potencia de React con tecnologías del lado del servidor probadas en la industria, como Node, Express y MongoDB, crea una amplia gama de posibilidades al desarrollar aplicaciones web del mundo real.

Este libro lo guía a través de la preparación del entorno de desarrollo para el desarrollo web basado en el stack MERN, para crear una aplicación básica de esqueleto y extenderla para construir cuatro aplicaciones web diferentes. Estas aplicaciones incluyen redes sociales, un mercado en línea, una transmisión de medios y una aplicación de juegos basada en la web con características de realidad virtual.

Mientras aprende a configurar la pila y desarrolla una amplia gama de aplicaciones con este libro, comprenderá el funcionamiento interno de la pila MERN, ampliará sus capacidades para funciones complejas y obtendrá un conocimiento práctico de cómo preparar aplicaciones basadas en MERN para cumplir Las crecientes demandas de las aplicaciones web del mundo real.

#### Estilo y enfoque

Este libro proporciona pautas prácticas para configurar y construir aplicaciones basadas en la pila MERN, a la vez que proporciona más explicaciones sobre conceptos e implementaciones clave.

Descarga del código de ejemplo para este libro Puede descargar los archivos de código de ejemplo para todos los libros de Packt que haya comprado en su cuenta en http://www.PacktPub.com. Si compró este libro en otro lugar, puede visitar http://www.PacktPub.com/support y registrarse para recibir los archivos directamente por correo electrónico.

#### Publisher Resources

Contenido suplementario: [https://github.com/PacktPublishing/Full-Stack-React-Projects](https://github.com/PacktPublishing/Full-Stack-React-Projects)


### Table of Contents

#### Title Page

#### Copyright and Credits

Full-Stack React Projects

#### Packt Upsell

Why subscribe?

PacktPub.com

#### Contributors

About the author

About the reviewer

Packt is searching for authors like you

#### Preface

Who this book is for

What this book covers

To get the most out of this book

Download the example code files

Conventions used

Get in touch

Reviews

#### Unleashing React Applications with MERN

##### MERN stack

Node

Express

MongoDB

React

##### Relevance of MERN

Consistency across the technology stack

Less time to learn, develop, deploy, and extend

Widely adopted in the industry

Community support and growth

##### Range of MERN applications

MERN applications developed in this book

Social media platform

Online marketplace

Media streaming application

VR game for the web

##### Book structure

Getting started with MERN

Building MERN from the ground up – a skeleton application

Developing basic web applications with MERN

Advancing to complex MERN applications

Going forward with MERN

##### Getting the most out of this book

##### Summary

#### Preparing the Development Environment

##### Selecting development tools

Workspace options

Local and cloud development

IDE or text editors

Chrome Developer Tools

Git

Installation

Remote Git hosting services

##### Setting up MERN stack technologies

MongoDB

Installation

Running the mongo shell

Node

Installation

Upgrading npm versions

Node version management with nvm

npm modules for MERN

Key modules

devDependency modules

##### Checking your development setup

Initializing package.json and installing npm modules

Configuring Babel, Webpack, and Nodemon

Babel

Webpack

Client-side Webpack configuration for development

Server-side Webpack configuration

Client-side Webpack configuration for production 

Nodemon

Frontend views with React

Server with Express and Node

Express app

Bundle React app during development

Serving static files from the dist folder

Rendering templates at the root 

Connecting the server to MongoDB

npm run scripts

Developing and debugging in real time

Summary

#### Building a Backend with MongoDB, Express, and Node

##### Skeleton application overview

Feature breakdown

Focus of this chapter – the backend

User model

API endpoints for user CRUD

Auth with JSON Web Tokens

How JWT works

##### Implementing the skeleton backend

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

#### Adding a React Frontend to Complete MERN

Skeleton frontend

Folder and file structure

Setting up for React development

Configuring Babel and Webpack

Babel

Webpack

Loading Webpack middleware for development

Serving static files with Express

Updating the template to load a bundled script

Adding React dependencies

React

React Router

Material-UI

Implementing React views

Rendering a home page

Entry point at main.js

Root React component

Customizing the Material-UI theme

Wrapping the root component with MUI theme and BrowserRouter

Marking the root component as hot-exported

Adding a home route to MainRouter

Home component

Imports

Style declarations

Component definition

PropTypes validation

Export component

Bundling image assets

Running and opening in the browser

Backend API integration

Fetch for User CRUD

Creating a user

Listing users

Reading a user profile

Updating a user's data

Deleting a user

Fetch for auth API

Sign-in

Sign-out

Auth in the frontend

Managing auth state

PrivateRoute component

User and auth components

Users component

Signup component 

Signin component

Profile component

EditProfile component

DeleteUser component

Menu component

Basic server-side rendering

Modules for server-side rendering

Preparing Material-UI styles for SSR

Generating markup

Sending a template with markup and CSS

Updating template.js

Updating MainRouter

Hydrate instead of render

Summary

#### Starting with a Simple Social Media Application

MERN Social

Updating the user profile

Adding an about description

Uploading a profile photo

Updating the user model to store a photo in MongoDB

Uploading a photo from the edit form

File input with Material-UI

Form submission with the file attached

Processing a request containing a file upload

Retrieving a profile photo

Profile photo URL

Showing a photo in a view

Following users in MERN Social

Follow and unfollow

Updating the user model

Updating the userByID controller method

API to follow and unfollow

Accessing follow and unfollow APIs in views

Follow and unfollow buttons

FollowProfileButton component

Update Profile component

Listing followings and followers

FollowGrid component

Finding people to follow

Fetching users not followed

FindPeople component

Posts

Mongoose schema model for Post

Newsfeed component

Listing posts

List in Newsfeed

Newsfeed API for posts

Fetching Newsfeed posts in the view

Listing by user in Profile

API for posts by a user

Fetching user posts in the view

Creating a new post

Creating post API

Retrieving a post's photo

Fetching the create post API in the view

NewPost component

Post component

Layout

Header

Content

Actions

Comments

Deleting a post

Likes

Like API

Unlike API

Checking if liked and counting likes

Handling like clicks

Comments

Adding a comment

Comment API

Writing something in the view

Listing comments

Deleting a comment

Uncomment API

Removing a comment from view

Comment count update

Summary

#### Exercising New MERN Skills with an Online Marketplace

MERN Marketplace

Users as sellers

Updating the user model

Updating the Edit Profile view

Updating the menu

Shops in the Marketplace

Shop model

Create a new shop

Create shop API

Fetch the create API in the view

NewShop component

List shops

List all shops

Shops list API

Fetch all shops for the view

Shops component

List shops by owner

Shops by owner API

Fetch all shops owned by a user for the view

MyShops component

Display a shop

Read a shop API

Fetch the shop in the view

Shop component 

Edit a shop

Edit shop API

Fetch the edit API in the view

EditShop component

Delete a shop

Delete shop API

Fetch the delete API in the view

DeleteShop component

Products

Product model

Create a new product

Create product API

Fetching the create API in the view

The NewProduct component

List products

List by shop

Products by shop API

Products component for buyers

MyProducts component for shop owners

List product suggestions

Latest products

Related products

Suggestions component

Display a product

Read a product API

Product component

Edit and delete a product

Edit

Delete

Product search with category

Categories API

Search products API

Fetch search results for the view

Search component

Categories component

Summary

#### Extending the Marketplace for Orders and Payments

The MERN Marketplace with a cart, payments, and orders

Shopping cart

Adding to cart

Cart icon on the menu

Cart view

The CartItems component

Retrieving cart details

Modifying quantity

Removing item

Showing total price

Option to check out

Using Stripe for payments

Stripe

Stripe-connected account for each seller

Updating user model

Button to connect with Stripe

The StripeConnect component

Stripe auth update API

Stripe Card Elements for checkout

Stripe Customer to record card details

Updating user model

Updating user controller

Creating a new Stripe Customer

Updating an existing Stripe Customer

Creating a charge for each product processed

Checkout

Initializing checkout details

Customer information

Delivery address

The PlaceOrder component

Stripe CardElement component

Placing an order

Empty cart

Redirecting to Order view

Creating new order

Order model

Ordered by and for customer

Delivery address

Payment reference

Products ordered

The CartItem schema

Create order API

Decrease product stock quantity

Create order controller method

Orders by shop

List by shop API

The ShopOrders component

List orders

The ProductOrderEdit component

APIs for products ordered

Get status values

Update order status

Cancel product order

Process charge for product

View order details

Summary

#### Building a Media Streaming Application

MERN Mediastream

Uploading and storing media

Media model

MongoDB GridFS to store large files

Creating a media API

Route to create media

Controller method to handle create request

Fetch create API in the view

New media form view

Adding media menu button

React route for NewMedia view

NewMedia component

Retrieve and stream media

Get video API

React media player to render the video

Media list

MediaList component

List popular media

List media by users

Display, update, and delete media

Display media

Read media API

Media component

Update media details

Media update API

Media edit form

Deleting media

The Delete media API

The DeleteMedia component

Summary

#### Customizing the Media Player and Improving SEO

MERN Mediastream with a custom media player

The play media page

Component structure

Related media list

Related list API

The RelatedMedia component

The PlayMedia component

Media player

Updating the Media component

Initializing the media player

Custom media controls

Play, pause, and replay

Play next

Loop on ended

Volume control

Progress control

Fullscreen

Played duration

Autoplaying related media

Toggling autoplay

Handle autoplay across components

Update state when video ends in MediaPlayer

Server-side rendering with data

Route config

Updating SSR code for the Express server

Using route config to load data

Isomorphic-fetch

Absolute URL

Injecting data into React app

Applying server-injected data in client code

Passing data props to PlayMedia from MainRouter

Rendering received data in PlayMedia

Checking the implementation of SSR with data

Test in Chrome

Loading a page with JS enabled

Disabling JS from settings

PlayMedia view with JS blocked

Summary

#### Developing a Web-Based VR Game

MERN VR Game

Game features

Focus of this chapter

React 360

Getting started with React 360

Key concepts for developing the VR game

Equirectangular panoramic images

3D position – coordinates and transforms

3D coordinate system

Transform

React 360 components

Core components

View

Text

Components for 3D VR experience

Entity

VrButton

React 360 API

Environment

Native Modules

AudioModule

Location

StyleSheet

VrHeadModel

Assets

React 360 input events

Game details

Game data structure

Details of VR objects

OBJ and MTL links

Translation values

Rotation values

Scale value

Color

Static data versus dynamic data

Sample data

Building the game view in React 360

Update client.js and mount to Location

Defining styles with StyleSheet

World background

Adding 3D VR objects

Interacting with VR objects

Rotation 

Animation with requestAnimationFrame

Clicking the 3D objects

Collecting the correct object on click

Game completed state

Bundling for production and integration with MERN

Bundling React 360 files

Integrating with MERN application

Add the React 360 production files

Updating references in index.html

Trying out the integration

Summary

#### Making the VR Game Dynamic Using MERN

Dynamic MERN VR Game

Game model

Game schema

VRObject schema

Array length validation in the game schema

Game APIs

The create API

Route

Controller 

Fetch

List API

Route

Controller 

Fetch

List by maker API

Route

Controller 

Fetch

Read API

Route

Controller 

Fetch

Edit API

Route

Controller 

Fetch

Delete API

Route

Controller

Fetch

Creating and editing games

Making a new game

Updating the menu

NewGame component

Editing the game

EditGame component

The GameForm component

Inputing simple game details

Form title

Game world image

Game name

Clue text

Handle input

Modifying arrays of VR objects

Iterating and rendering the object details form

Adding a new object to the array

Removing an object from the array

Handling the object detail change

VRObjectForm component

3D object file input

Translate value input

Rotate value input

Scale value input

Object color input

Delete object button

Handling the input change

Game list views

All games

Games by a maker

GameDetail component

Game details

Play Game button

Edit and delete buttons

Deleting a game

DeleteGame component

Playing the VR game

API to render the VR game view

Updating the game code in React 360

Getting the game ID from a link

Fetching the game data with the read API

Bundling and integrating the updated code

Summary

#### Following Best Practices and Developing MERN Further

Separation of concerns with modularity

Revisiting the application folder structure

Server-side code

Client-side code

Adding CSS styles

External style sheets 

Inline styles

JSS

Selective server-side rendering with data

When is SSR with data relevant?

Using ES6 class for stateful vs pure functional components

React components with ES6 class

React components as pure functions

Designing the UI with stateful components and stateless functional components

Using Redux or Flux 

Enhancing security

JSON web tokens – client-side or server-side storage

Securing password storage

Writing test code

Testing with Jest

Adding a test to the MERN Social application

Installing the packages

Defining the script to run tests

Adding a tests folder

Test case

Adding the test

Generating a snapshot of the correct Post view

Running and checking the test

Optimizing the bundle size

Code splitting

Dynamic import()

Extending the applications

Extending the server code

Adding a model

Implementing the APIs

Adding controllers

Adding routes

Extending the client code

Adding the API fetch methods

Adding components

Loading new components

Updating frontend routes

Integrating with existing components

Summary

#### Other Books You May Enjoy

Leave a review - let other readers know what you think
