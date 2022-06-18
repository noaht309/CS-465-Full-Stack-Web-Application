# CS-465-Full-Stack-Development-I
Repository for CS-465 Full Stack Development I course assignments and projects for Noah Archibald.


Architecture:

For the frontend of this web application we used Express HTML for the customer facing aspect of the website, as well as AngularJS to develop single page applications for administrative use. Express HTML was used to serve the Javascript documents to the website and utilizing this MVC architecture means that multiple pages are loaded every time a user interacts with the website, which is significantly slower compared to the AngularJS single page applications. The backend of the website utilized a NoSQL database along with MongoDB as it integrates well with the NodeJS environment the website was built around. It also allows for the conversion of documents to and from JSON in a relatively hassle free manner.



Functionality:

In this application JSON is used as a way to to store data and also display it to the user. MongoDB stores its data in a BSON format, so a relatively simple conversion process is required to bring the data from the backend to the frontend and display it as JSON with the help of HandleBars and TypeScript. Angular allows for simple commands to be inserted into HTML templates that efficiently displays all the data in the database query with a very small amount of coding required. In that aspect, the reusable code templates that we continually used throughout the development process made code much more cohesive and the logic easier to follow overall.


Testing:

Security for any public facing website is incredibly vital, as it will inevitably be examined and scrutizined by unsavory actors. To that end, in this application the administrator side of the website uses passwords encrypted with hashes to send to and from the database, as opposed to sending the raw data. Also, being mindful of including the various sensitive security features to the .gitignore file when uploading the final application is vital in protecting the integrity of the various security mechanisms programmed into the application. Verification before allowing a user access to the API is also important, so various steps had to be taken to verify the validity of the credentials provided by the user with those stored on the database.


Reflection:
This course has been a very helpful guide in understanding the aspects that go into creating a full-stack web application. The integration of the various frameworks and languages in the MEAN stack, and actually working with them hands on in a programming enviornment rather than reading about them in theory, helped to further cement my understanding of the tasks invovled and how to efficiently plan out the development of a web application. It was also good to walk through the logic that dictated the various important aspects of the program and how they ultimately impacted the final development environment.
