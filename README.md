# Book_Search_Engine

## Task

Our assignment is emblematic of the fact that most modern websites are driven by two things: data and user demands. This shouldn't come as a surprise, as the ability to personalize user data is the cornerstone of real-world web development today. And as user demands evolve, applications need to be more performant.

We take starter code with a fully functioning Google Books API search engine built with a RESTful API, and refactor it to be a GraphQL API built with Apollo Server. The app was built using the MERN stack with a React front end, MongoDB database, and Node.js/Express.js server and API. It's already set up to allow users to save book searches to the back end. 

## User Story

```md
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```

## Description

 ![License](https://img.shields.io/badge/License-MIT-yellow)

```md
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button  
```

## Mock-Up

Let's start by revisiting the web application's appearance and functionality.

As you can see in the following animation, a user can type a search term (in this case, "star wars") in a search box and the results appear:

![Animation shows "star wars" typed into a search box and books about Star Wars appearing as results.](./Assets/21-mern-homework-demo-01.gif)

The user can save books by clicking "Save This Book!" under each search result, as shown in the following animation:

![Animation shows user clicking "Save This Book!" button to save books that appear in search results. The button label changes to "Book Already Saved" after it is clicked and the book is saved.](./Assets/21-mern-homework-demo-02.gif)

A user can view their saved books on a separate page, as shown in the following animation:

![The Viewing Lernantino's Books page shows the books that the user Lernaninto has saved.](./Assets/21-mern-homework-demo-03.gif)

## Table Of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Test](#test)
- [License](#license)
- [Contribution](#contribution)
- [Contact](#contact)
- [Questions](#questions)
    
## Installation 

The following necessary dependencies must be installed to run the application.

 mongoDB Atlas, Express, mongoose, GraphQL, compression, apollo-server-express, Heroku

## Usage

 Application can be invoked by npm start or  node server.js command in terminal or user can use deployed to Heroku link to access application.

## Test
  N/A
## License

This project is licensed under :

 [MIT](https://opensource.org/licenses/MIT)

For more information about the license, check the above link.

## Contribution

Coding Boot camp provided starter code.

## Contact

* GitHub :[bindi-v](https://github.com/bindi-v)

* Email : bindi.vaghela@gmail.com
    
## Questions

If you have any questions, please reach out to my Github.

### Deployed Link

* [The URL to the deployed to Heroku application]()

* [The URL to the Github repository](https://github.com/bindi-v/Book_Search_Engine)

#### Thank you for visiting my Github!