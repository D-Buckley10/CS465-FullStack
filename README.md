# CS465-FullStack
CS-465 Full Stack Development with MEAN

## Architecture 
### Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

The frontend development methods that I worked with did involve working with Express HTML, Javasript, and utilizing Angular for developing a single-page application. When working with Express HTML, I learned how to implement features such as handlebars (.hbs) and partials to make the code more modularized and friendly to implement changes. Javascript was utilized here to display data and add functionality to this portion of the website. When developing the SPA Angular.js and TypeScript were used to create functionality while the HTML components were used page layyout.

### Why did the backend use a NoSQL MongoDB database?

MongoDB was used to store the information about the trips that would need to be accessed, updated, deleted, or added upon. The reason we utilized a NoSQL database was since the data we were working with was in JSON format, where a SQL database works with tables of fixed rows and columns.

## Functionality 
### How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

JSON isn't a programming language, unlike Javascript, but instead a formatting style in which data is stored and transported in name-value pairs. Data that is stored in MongoDB stores data is BSON, which is quite similar to JSON. When the frontend makes a request to the backend, the data is sent in JSON for easy transportation of the data. THe JSON request is fed through the backend and then asked through the database, which will find the entry within it based on the JSON data that was sent from the frontend.

### Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components

In the application that I created, the use of partials and handlebars were implemented in the Express HTML component of the website. For the backend SPA, the trip card component is capable to be duplicated for the amount of trips that exist in the database as well as display the unique information for each trip. The benefits that come from having reusable user interface components is the ability to use these components across multiple pages of the website. In the case of the backend, it makes the information that is displayed uniform and appealing to look at.

## Testing 
### Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.



### Reflection 
How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
