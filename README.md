# 📚 Book Club 📚

Welcome to Book Club--your new go-to app where you can find out all the details about the latest bestsellers! If you're a book lover, you've come to the right place.

Deployed Application here: [Book Club](https://book-club-ui.herokuapp.com/)

# Table of Contents

1. [Overview](#overview)
2. [Installation Instructions](#installationInstructions)
3. [Project Goals](#projectGoals)
4. [Directions and Features](#directions)
5. [Code Architecture](#codeArchitecture)
6. [Technologies Used](#techUsed)
7. [Testing](#testing)
8. [Project Challanges](#projectChallanges)
9. [Project Wins](#projectWins)
10. [Future Iterations](#futureIterations)
11. [Authors](#authors)

## Overview <a name="overview"></a>

Book Club is a project at the Turing School of Software and Design that was built with `create-react-app` and tested using Cypress. React, React Router and data pulled from a backend server we created were utilized to display a dashboard of books. The user can select a single book by clicking on the 'Learn More' button to get more information about it. Additionally, the user will find Book Club to be a responsively designed application that they may use on many different screens.

We created a backend for this project to satisfy the requirements of our Stretch Tech Project. We were given an 8 day timeframe to learn and implement new technologies such as Express, Node, PostgresSQL, Knex to build a backend server and database. 

- Project Spec here: [Stretch](https://frontend.turing.edu/projects/module-3/stretch.html)
- Book Club API: 
    - GitHub: [Book Club API](https://github.com/cagallo/book-club-api)
    - Heroku: [Book Club API](https://book-club-api-2110.herokuapp.com/api/v1/books)


## Installation Instructions <a name="installationInstructions"></a>

1. Clone down [this repository](https://github.com/ectweitmann/book-club-ui)
2. Run `npm install`
3. Run `npm start` in your terminal
4. Go to http://localhost:3000/ and you should see the website
5. Enter `control + c` in your terminal to stop the server at any time.

## Project Goals <a name="projectGoals"></a>

- Continue to gain competency with React fundamentals, Router and Cypress testing
- Practice building a server in Express 
- Successful populate a PostgreSQL database using Knex query builder
- Learn how to deploy an API with a PostgreSQL database on Heroku
- Gain an understanding of what is it like to create both the frontend and the backend of an application


## Directions and Features <a name="directions"></a>

Scroll through the main page to view all books in the database. Each books's cover, title and author are visible. 

![main_page_view](https://media.giphy.com/media/7Q9UX06Z6FbB40wdEP/giphy.gif)

Click on the 'Learn More' button next to a book cover that interests you to view a book's details. On this page a description of the book's plot is presented. The user is also given the ability to add to or remove a book from their favorites as well as the option to buy the book on Amazon. They can view all of their favorited books by clicking the "Your favorites" button at the top right of the page. Click the book club logo at the top left of the page to return to the main page.

![favorite-unfavorite-book](https://media.giphy.com/media/m2txGQ1Ikbi4EJ9k5L/giphy.gif)

## Code Architecture <a name="codeArchitecture"></a>

The React architecture is based on three class components (App.js, BookDetails.js, Favorites.js) and five functional components (Nav.js, Error404.js, BookContainer.js, BookCard.js, ErrorModal.js). The class components hold state and are in charge of the network requests, while the functional components render information passed down as props.

## Technologies Used <a name="techUsed"></a>

### Frontend Technologies
- React
- React Router
- Javascript
- CSS3
- HTML5
- Fetch API
- webpack
- PropTypes
- NPM
- Cypress
- title-case

### Backend Technologies

- Express
- PostgreSQL
- Knex.js
- JavaScript
- Node.js
- Node Fetch
- PgAdmin4
- Heroku
- Postman
- NPM

## Testing <a name="testing"></a>

Cypress was used for E2E and integration testing. To test the application: run `npm run cypress` and you will have a window open that gives you the ability to click on each test and see whether they pass. Make sure you've run `npm start` in a separate terminal tab before you begin the testing. 

<img width="784" alt="Screen Shot 2022-02-27 at 4 13 13 PM" src="https://user-images.githubusercontent.com/78453792/155904096-2c56df5b-8948-45f3-9356-b3c2b466df18.png">

Example of a successful test:

![bc-test-gif](https://user-images.githubusercontent.com/78453792/155904117-943b901c-4006-473b-93d1-09a56a7eca94.gif)

## Project Challanges <a name="projectChallanges"></a>

- This was our team's first time working with the following technologies and concepts, which naturally came with a learning curve as we implemented them into our project:

    - Connecting Express server to PostgresSQL database using Knex
    - Deploying app using Heroku Postgres

This project was a really "stretch" for our group--we had never worked with PostgreSQL or Knex before so it was a huge challenge learning how to connect our server to the database using Knex. We came in without any knowledge of mySQL and had difficulities with the complexities of the Knex documentation. Most of our challanges came from using the Knex query builder due to our inexperience with the backend. We also ran into trouble when trying to deploy to Heroku Postgres due to not being very familar with process.ENV and environments in general.  

## Project Wins <a name="projectWins"></a>

- Created a fully funtional MVP with time scope of 8 days
- Continued to build a strong understanding of React framework 
- Successfully built an API with database by self-teaching Express, PostgreSQL and Knex. 
- Completed a thorough project plan and wireframe, which kept our team on track 
- Implemented React Router for a multi-page UX
- Continued to gain competency with Cypress E2E testing framework
- Utilized typechecking with PropTypes

## Future Iterations <a name="futureIterations"></a>

- A login page with authorization for users where they could store books to their favorites and could add their ratings/reviews
- Create a reading list for users to be able to add books that they plan to read 
- A search bar to quickly filter a book by title or author
- An option for users to sort books by rating or filter by genre

## Authors

- [Kayla Durrett](https://github.com/krdurrett)
- [Chez Gallo](https://github.com/cagallo)
- [Christine Rowland](https://github.com/Fordo29)
- [Ethan Tweitmann](https://github.com/ectweitmann)

- Project Manager: [Robbie Jaeger](https://github.com/robbiejaeger)

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).





