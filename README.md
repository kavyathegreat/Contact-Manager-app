# Contact Management App

This project is a Contact Management App built with Express.js and MongoDB. The video tutorial covers setting up the project, creating an Express server, handling routes, and performing CRUD operations for contacts and users.

## Table of Contents
- [Introduction](#introduction)
- [Project Setup](#project-setup)
- [Creating an Express Server](#creating-an-express-server)
- [Setting Up Thunder Client](#setting-up-thunder-client)
- [Express Router & Contacts CRUD Routes](#express-router--contacts-crud-routes)
- [Contact Controller for CRUD Operations](#contact-controller-for-crud-operations)
- [Handling HTTP Methods](#handling-http-methods)
- [Middleware for POST Requests](#middleware-for-post-requests)
- [Error Handling](#error-handling)
- [Async Handler](#async-handler)
- [MongoDB Setup](#mongodb-setup)
- [Connecting Express to MongoDB](#connecting-express-to-mongodb)
- [Mongoose Schema for Contacts](#mongoose-schema-for-contacts)
- [CRUD Operations for Contacts](#crud-operations-for-contacts)
  - [Get All Contacts](#get-all-contacts)
  - [Create New Contact](#create-new-contact)
  - [Get Contact](#get-contact)
  - [Update Contact](#update-contact)
  - [Delete Contact](#delete-contact)
- [User Routes](#user-routes)
- [User Controller](#user-controller)
- [Mongoose Schema for User](#mongoose-schema-for-user)
- [User Registration and Password Hashing](#user-registration-and-password-hashing)
- [JWT Access Token and User Login](#jwt-access-token-and-user-login)
- [Protecting Routes](#protecting-routes)
  - [Verify JWT Token Middleware](#verify-jwt-token-middleware)
- [User and Contact Relationship](#user-and-contact-relationship)
  - [Logged in User Get All Contacts](#logged-in-user-get-all-contacts)
  - [Logged in User Create New Contact](#logged-in-user-create-new-contact)
  - [Logged in User Update and Delete Contact](#logged-in-user-update-and-delete-contact)
- [Outro](#outro)

## Introduction

Overview of the project and REST API conventions.

## Project Setup

Setting up the project structure for the Contact Management App.

## Creating an Express Server

Creating an Express server for handling requests.

## Setting Up Thunder Client

Setting up Thunder Client for testing the API.

## Express Router & Contacts CRUD Routes

Setting up Express Router and CRUD routes for contacts.

## Contact Controller for CRUD Operations

Creating a Contact Controller to handle CRUD operations.

## Handling HTTP Methods

Handling multiple HTTP methods per route.

## Middleware for POST Requests

Using built-in middleware to handle POST request bodies.

## Error Handling

Throwing and handling errors using middleware.

## Async Handler

Using an async handler for asynchronous operations.

## MongoDB Setup

Setting up MongoDB for the project.

## Connecting Express to MongoDB

Connecting the Express app to the MongoDB database.

## Mongoose Schema for Contacts

Creating a Mongoose schema for contacts.

## CRUD Operations for Contacts

### Get All Contacts

Implementing the GET all contacts operation.

### Create New Contact

Implementing the POST create new contact operation.

### Get Contact

Implementing the GET single contact operation.

### Update Contact

Implementing the PUT update contact operation.

### Delete Contact

Implementing the DELETE contact operation.

## User Routes

Adding routes for user registration, login, and getting current user.

## User Controller

Creating a User Controller for handling user-related operations.

## Mongoose Schema for User

Creating a Mongoose schema for users.

## User Registration and Password Hashing

Implementing user registration and hashing passwords.

## JWT Access Token and User Login

Generating JWT access tokens and implementing user login.

## Protecting Routes

### Verify JWT Token Middleware

Creating middleware to verify JWT tokens and protect routes.

## User and Contact Relationship

Handling the relationship between users and contacts.

### Logged in User Get All Contacts

Implementing GET all contacts for the logged-in user.

### Logged in User Create New Contact

Implementing POST create new contact for the logged-in user.

### Logged in User Update and Delete Contact

Implementing PUT update and DELETE contact for the logged-in user.

