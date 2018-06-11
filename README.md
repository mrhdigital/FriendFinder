# FriendFinder

### Synopsis
***

This friend matching app is a full-stack site implemented with node and express.This site will take in results based on a user survey, then compare their answers with those from other users. The app will then display the name and picture of the user with the best overall match.
[Here is the live version](https:#)

### User Interface


Best Friend Finder works as follows:

1. Users are welcomed to Best Friend Finder on the site's landing page

2. There is a call to action button to take the quiz and be matched with a best friend

3. On the quiz page, users enter their name and a link to a photo 

4. Next, they react to ten statements using a 1 (strongly disagree) through 5 (strongly agree)

5. When the user hits submit, the app compares the user's total score to the potential friends who are already in the database 

6. The friend with the lowest absolute numerical difference is displayed in a modal view. Once the modal is dismissed, the user is returned to the landing page.

### Technical Notes
The application utilizes the following tech/librarys:
  1. Front-end:
    * HTML/CSS/Javascript
    * jQuery
    * Bootstrap
    * Google Fonts
  2. Back-end:
    * Node.JS
    * Express
    * NPM
  3. Deployment
    * Heroku 

### NPM Packages  

  * express
  * body-parser
  * path

### html-routes.js

  * A GET Route to /survey displays the survey page.
  * A default USE route that leads to home.html which displays the home page
  
### api-routes.js 
 
 * A GET route with the url /api/friends is used to display a JSON of all possible friends.
 
 * A POST routes /api/friends. is used to handle incoming survey results. This route is also used to handle the compatibility logic.
    

