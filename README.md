
﻿
# Quiz App

The Quiz App is a web application that lets you create and share quizzes with your friends. The creator of the quiz can view and share all the results at the end of the quiz.

## Creators

[Abdul Syed](https://github.com/syabdulr)  
[Aryan Ahmadi](https://github.com/arianah75)  
[Bea Mungcal ](https://github.com/segvndo)

## Getting Started

1. Create the `.env` by using `.env.example` as a reference: `cp .env.example .env`
2. Update the .env file with your correct local information 
  - username: `labber` 
  - password: `labber` 
  - database: `midterm`
3. Install dependencies: `npm i`
4. Fix to binaries for sass: `npm rebuild node-sass`
5. Reset database: `npm run db:reset`
  - Check the db folder to see what gets created and seeded in the SDB
7. Run the server: `npm run local`
  - Note: nodemon is used, so you should not have to restart your server
8. Visit `http://localhost:8080/`

## Features

- Features
- Users can create quizzes.
- Users can make their quizzes unlisted.
- Users can share a link to a single quiz.
- Users can see a list of public quizzes.
- Users can see a list of public quizzes on the home page.
- Users can attempt a quiz.
- Users can see the results of their recent attempt.
- Users can share a link to the result of their attempt.

## Tech Stack

Tech Stack
Node.js
Express
PostgreSQL
jQuery
SASS
EJS


## Warnings & Tips

- Do not edit the `layout.css` file directly, it is auto-generated by `layout.scss`.
- Split routes into their own resource-based file names, as demonstrated with `users.js` and `widgets.js`.
- Split database schema (table definitions) and seeds (inserts) into separate files, one per table. See `db` folder for pre-populated examples. 
- Use helper functions to run your SQL queries and clean up any data coming back from the database. See `db/queries` for pre-populated examples.
- Use the `npm run db:reset` command each time there is a change to the database schema or seeds. 
  - It runs through each of the files, in order, and executes them against the database. 
  - Note: you will lose all newly created (test) data each time this is run, since the schema files will tend to `DROP` the tables and recreate them.

## Dependencies

- Node 10.x or above
- NPM 5.x or above
- PG 6.x

## Production Dependencies

- bcrypt          5.1.0,
- chalk           2.4.2,
- cookie-session  2.0.0,
- dotenv          2.0.0,
- ejs             2.7.4,
- express         4.18.2,
- express-session 1.17.3,
- morgan"         1.10.0",
- pg              8.11.0,
- sass            1.35.1

## Development Dependencies

- nodemon         2.0.22


Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
