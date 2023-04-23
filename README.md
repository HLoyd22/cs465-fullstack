#CS-465 Full Stack Development with MEAN
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Architecture
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Express HTML, JavaScript, and a single-page application (SPA) were all used in this full stack project. All used a different type of frontend development. For the
website frontend, it used a combination of HTML and JavaScript. The JavaScript was used for the routers, controllers, and the models. This also included the main
application file. Ths exported the Express application. The SPA application ony operates on a single page. This focuses on providing any admin functions for easy
maintenance and updates for the website. The Express pages will functions off the handlebar view and the HTML pages.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Why did the backend use a NoSQL MongoDB database?
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The backend used a NoSQL MongoDB database in orcder to hold the information for the user. This information could be information about the users trip to their sensitive
login data. The NoSQL does not rely on schema. This makes it easier for the users to store and modify their data.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Functionality
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The main difference between JSON and JavaScript is that JSON is mainly used for the purpose of storing data. JSON cannot include functions, however, JavaScript objects
can include functions. These functions can only be used in JavaScript while JSON can be used by other languages that we might use. JavaScript can convert JSON data
becuase of their similar system. JSON data is what is transmitted for communication from the backend to the frontend.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user 
interface (UI) components.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

There are two examples that can be given of refactoring the code in the project to help improve functionality. The first was moving the duplicated HTML code to 
components. This could be called from each page just by updating the pages to dynamically load records from the database. The second was making the header and the 
footer into partials. This allowed the handlebars to call in a file and have the header and the footer displayed.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Testing
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. 
Explain your understanding of methods, endpoints, and security in a full stack application.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The API endpoints in this application was used to validate the user and authorize the user to alter the information for the trips in the database. The endpoints are
used in combination with certain data methods such as, GET, POST, and PUT. Applying security for these endpoints are essential. If there is no protection unauthorized
users would be able to gain access to all information in the database and have free rein over the website.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Reflection
------------------------------------------------------------------------------------------------------------------------------------------------------------------------
How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more 
marketable candidate in your career field?
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

As someone who wants to work in web design this course allowed me to see other ways into making a secure website. Through backend and frontend development. While this
class did have some ups and downs with my learning curve, I think that I was able to fully grasp the skills that were being taught. I learned a better understanding on
how many components link together. Also using these to make a better product in the end. 
