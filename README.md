# Social-Network-API

## Description

This is an API for a social network web application.  It allows users to share their thoughts, react to friends' thoughts, and create a friend list. 

## Table of Contents
* [User Story and Acceptance Criteria](#user-story-and-acceptance-criteria)
* [Built With](#built-with)
* [Installation](#installation)
* [Links](#links)

---
## User Story and Acceptance Criteria


### User Story

```
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

### Acceptance Criteria

```
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
```
```
WHEN I open API GET routes in Insomnia Core for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
```
```
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete users and thoughts in my database
```
```
WHEN I test API POST and DELETE routes in Insomnia Core
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```
---
## Built With

* Node
* Express
* MongoDb
* Mongoose ODM

---
## Installation
* Both Node.js and MongoDB must be installed on your computer
* Clone the repo https://github.com/sgenesi/social-network-API 
* Navigate to your root directory and run <code>npm install</code>
* To start server, run <code>npm start</code> in your command line

---
## Links
* Walk Through Video: https://screencast-o-matic.com/watch/crerqfVV1Hi
* GitHub Repo: https://github.com/sgenesi/social-network-API 

