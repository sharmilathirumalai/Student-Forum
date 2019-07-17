# Student Forum
The main purpose of this web application is to create a **tailor-made forum for students**. With a plethora of online forums, there doesn't exist a customized forum for students. Recognizing the importance of the educational forum, the intention is to create a forum that facilitates interactions and learnings outside the classroom.

  Application is live at [Frontend](https://student-forum-2020.herokuapp.com/home) and [Web Service](https://forum-webservice.herokuapp.com/).

## What are the framework & libraries used ?
This application is built using the following frameworks and libraries :package:.
* [Angular 7](https://angular.io/) - Web application framework
* [Bootstrap](https://getbootstrap.com/)  - CSS Framework
* [Google Fonts](https://fonts.google.com/) - Web Fonts Library
* [HTML and CSS](https://www.w3schools.com/html/)- Web designing Language
* [Sails JS](https://sailsjs.com/) - MVC Framework to build Web Services.
* [MongoDB](https://www.mongodb.com/) - NoSQL Database used for data storage.


## What are the prerequisite required ?
 * Node JS - [Install](https://nodejs.org/en/download/)
 * Angular 7 - [Install](https://angular.io/guide/setup-local)
 * Sails JS - [Install](https://sailsjs.com/get-started)

## How to run the application ?
1. Clone the repo to your local machine using `git clone https://git.cs.dal.ca/sharmila/A2_Sharmila_Thirumalainathan.git`
2. Navigate to the workspace folder using `cd student-forum`

### Front End
3. Navigate to front workspace using `cd Frontend`
4. Launch the app using `ng serve --open`
5. Now the application will open in your default browser in following URL [localhost:4200](http:\\localhost:4200\home).

### Back End
6. Navigate to front workspace using `cd Backend\app`
7. Run the server by using `sails lift`
8. Now the server will be up in following URL [localhost:1337](http:\\localhost:1337).

**Note** The above steps will succeed only if the prerequisite platforms are installed in your local machine.

## What you can expect to see in here ?
The following are the pages that I've developed as the part of the student forum application

### Feature Owner - Sharmila Thirumalainathan
1. [Login](https://student-forum-2019.herokuapp.com/login) - This page allows the user (both professor & student) to sign into the application. Session Management is done by maintaining  'sid' between client and server.
2. [Signup](https://student-forum-2019.herokuapp.com/signup) - This page allows the user to signup for the application. Once the user has signed-in, he/she will be logged in and the session will also be created simultaneously.
3. [Reset](https://student-forum-2019.herokuapp.com/reset) - This page allow the user to reset the password if they've forgotten the password.
4. Logout - An option to logout and reset the user session.

### Feature Owner - Nirav Solanki

### Feature Owner - Nishant Bhambhani



## Application tour :rocket:
Now let us go for around to visit the above pages.

### Feature Owner - Nirav Solanki
* This feature requires the user to be logged in to the website.
* After, logging in the user must navigate to discussion from the right-hand side navigation bar. From here the user can click on “+” symbol to add a new post.
* The user will then be routed to the discussion list page, where the user can see the entry posted by him.

## Design Credits :art:

#### Inspirations
* Landing Page - [Moz](https://instapage.com/blog/landing-page-examples)
* Dashboard - [Bootstrap Theme](https://getbootstrap.com/docs/4.1/examples/dashboard/#)
* Login - [Bootstrap Templates](https://freshdesignweb.com/css-login-form-templates/)

#### Image Credits

* Landing page students image - [KissPNG](https://www.kisspng.com/png-international-student-scholarship-university-colle-442497/)
* Profile Picture - [Tumblr](https://www.tumblr.com/search/chandler%20icons%20season%202)

#### Tools

* Logo Generator - [Hatchful](https://hatchful.shopify.com/)
* Image Editing - [Pixlr](https://pixlr.com/x/)
* Code Editor - [Atom](https://atom.io/)
* Versioning - [Gitlab](https://git.cs.dal.ca/sharmila/A2_Sharmila_Thirumalainathan)

## Other references

1. A free tutorial to learn HTML and CSS. (n.d.). Retrieved from https://marksheet.io/sass-scss-less.html
2. Angular Getting Started Tutorial. (n.d.). Retrieved May 30, 2019, from https://angular.io/tutorial
3. Futur, T. (2015, August 12). What is UX Design? Defining User Experience Design & Explaining the Process. Retrieved from https://www.youtube.com/watch?v=CJnfAXlBRTE
4. Holeczek, Ł. (n.d.). Bootstrap cards. Retrieved from https://coreui.io/docs/components/cards/
5. The Most Important Color In UI Design. (2017, November 03). Retrieved from https://blog.marvelapp.com/important-color-ui-design/
6. Wanyoike, M. (2018, October 25). History of front-end frameworks. Retrieved from https://logrocket.com/blog/history-of-frontend-frameworks/

## Authors
- Sharmila Thirumalainathan, *B00823668*.
- Nirav Solanki, *B00808427*
- Nishant Bhambhani, *B00823348*
