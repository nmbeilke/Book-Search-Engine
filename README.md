# Homework-Book-Search-Engine
Google Books API search engine using React, GraphQL and Apollo Server.

We were given starter code with a fully functioning Google Books API search engine built with a React front end, MongoDB database, and Node.js/Express.js server and API. The assignment was to refactor it to be a GraphQL API built with Apollo Server using the following acceptance criteria:
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
- **What was your motivation?**
```md
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase

```
  
- **Why did you build this project?**
I built this project to practice using the GraphQL and Apollo server.

- **What problem does it solve?**
This allows users to be able to find and save books.

- **What did you learn?**
I learned how GraphQL and linking with Apollo differ from using MongoDB and Express along with some pros and cons to each.

- **What challenges did you encounter?**
Deploying to Heroku.
  
 
 ## Usage
 
 Link to live application: https://glacial-fortress-25025.herokuapp.com/ (WIP)


## Credits  
Assignment from The Coding Boot Camp at UC San Diego Extension in Partnership With Trilogy Education Services, LLC, Full Stack Part-Time Flex, September 2021 Cohort
