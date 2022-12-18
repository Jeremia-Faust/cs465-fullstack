# cs465-fullstack
CS-465Full Stack Development with MEAN

Architecture
In web development there are two sides of the same coin that work together to create a Dynamic webpage. The first is front-end web development or client-side development for which interactive webpages are created. The tool that frontend developers use is CSS (Cascading Style Sheets) is used to style and lay out web pages, HTML5, and JavaScript which are used for coding. The second side is Back-end web development or the server side that focuses on databases and coding. This is where the data is managed and the connection between the client side and databases are created. Full stack development with MEAN allows us to create interactive webpages where the data is stored on database then is accessed by the webpage. The website for Travlr Getaway webpage is dynamic and needs the ability to control the data shown on the website, this is done using an administrator single page application or (SPA).

Both Angular and express HTML are the most popular frameworks in use today. Both use a model called Model-View-Controller patterns. Express HTML is very simple were as Angular is very dynamic. Express is completely written in JavaScript and has many different libraries and plugins that make it very easy to customize. Express is very useful when working with APIs and has been optimized for security, which is why it is part of the mean structure. Angular is written by typescript and is much faster than Express. It is generally used in high traffic sites. What makes Angular stand out is its Dynamic UI and two-way binding that is the core of its architecture. 

Angular is very complex and robust and is great in large sites but for smaller sites the ease of express and simple file structure allows for quick and easy builds. There is no right or wrong in choosing which framework to use, it all really depends on the needs of the project. SPA or single page applications tend to take longer to load because it loads everything once, but that technique also provides very fast response times. They provide a seamless user experience because they do not have to navigate to different pages, but this also is a disadvantage due to there not being a way back to previous content
MongoDB is a NoSQL database that has the ability to hold large amounts of data. Data then can be sorted using the collections feature. This will be important for the Travlr website as it uses different types of data such as travel location, types of room available, or information on meals available. This data can be controlled within PowerShell or using the administrator single page application or (SPA).
Functionality
JavaScript is a programing language that is mainly used in web building. It has become the go to technology for any web building. JavaScript Object Notation or JSON is a data format the works well with many different technologies and is the sole format for mongoDB. Since JSON is used across many different technologies, it allows for the mean stack to pull the data from the backend to the frontend with no issues. This means that the data only needs to be stored once and can be reused throughout the entire program.
When we first started to turn this application into a dynamic website, we needed to make some changes. One glaring problem was all the data for the site was hardcoded directly on the site. We took this data and converted it into JSON format and loaded it into a database in this case mongoDB. Another thing we needed to do is to refactor the html code to make use of the handlebar technology. We then create reusable html handlebars for the footer and header. What this did was remove hundreds of lines of code thus reducing the load on the server.  
Testing
When testing that my SPA page was working, I used a few different techniques. That first and most useful was the website web developer tools console. Any errors in the use of the site will show up here. It allows you to narrow down problems very quickly. Windows PowerShell was useful to see the get and put data was working. Finally, postman and MongoDB compass allows me to see that data flow and endpoints. For security I added a login screen with an encrypted password using the library express-jwt encryption. So now when a user enters the site, they will not have the ability to add or edit the trips. When an authorized user logs in, the buttons will appear thus allowing them to edit or add trips.  
There are currently four endpoints for this application 

Method	Purpose	                       URL	                  Notes
GET	   <Retrieve the list of trips>	   </api/trips>          <Returns all active trips>
GET	   <Retrieve single trip>	         </api/trips/’code’>   <Returns single trip instance, identified by the trip ID or ‘code’ passed on the request URL>
POST	 Post new user	                 </api/resiter>        <Create new user for application 
POST	 Post user login	                /api/login	         <Login into application and return password token

. 


Reflection
In my professional life this course has shown me another avenue that I can pursue and to become completive in the job market. This course was very important in showing me how everything that I have done in past courses can be used to create amazing applications. It has given me a better understanding of solving problems and how different components of an application work together to provide a dynamic and secure application. 

