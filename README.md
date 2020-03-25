# CPSC-349-Project-1
Project 1 for CPSC 349

Blockbluster - A DVD Rental Website

Group Members:
Pia Wetzel


Installation

Install WAMP (Windows) or XAMPP onto your machine
Clone or Download our repository from https://github.com/oh-no-a-porcupine/DVD_rental
Place DVD_rental into your existing www directory
Create a Database named project1_1 and navigate to it
Use project1_1.sql to initialize the database
Optional: Modify username/password parameters inside sql_connect.php to connect to the database


User Manual

About Site
Blockbluster is a video rental application, users can search for movies by their titles and can either choose to rent them or to instead read/write reviews.
	
Home
Default page of the site, use the navigation bar to reach other pages

Navigation Bar
- 3 Tabs available, Home, About Us, and Search, clicking a tab takes you to that page
- Manual covers areas that are extensions from Search.

Search
- On any page click the Search tab on the navigation bar to go to search.php
- On search.php input a title (full or partial) into the input field added to the navigation bar
- Click search to search matching titles in the database
- Database returns movies that match titles and output is listed


Movie Details
- Search for a movie via the search bar
- Click on any movie returned by the search request to see movie details such as reviews, ratings, and rent/review options

Rent
 - Search for a movie via the search bar
 - Click on any movie returned by the search request to see movie details 
 - Click the “Rent DVD” button on the right side of the movie details page
 - You are redirected to a page assisting you with the checkout process
 - Enter your shipping and payment information and confirm by clicking the “Pay now!” button    

Review
 - Search for a movie via the search bar
 - Click on any movie returned by search request to see movie details 
 - Click “Review Movie” button on the right side of the movie details page
 - You are redirected to the review page
 - Enter your *user name, *password, rating and review and confirm by clicking the "Review"   button.    

*Note: if you are not a registered user, your account will be created automatically when reviewing a movie.
