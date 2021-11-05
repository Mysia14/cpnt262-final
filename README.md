# CPNT 262 Final Project - Deployed Product/Services Website
# International Food ****

## General Information

- Course: CPNT-262 - Web Client & Server Prog.
- Contributors:
  - [Mysia](https://github.com/Mysia14)
  - [James](https://github.com/Archangel767)
  - [Jean Marc](https://github.com/QDetectiveP)
  
- GitHub Links:
  - [GH repo](https://github.com/)
  - [Deployed Heroku URL](https://.herokuapp.com/)

### Context

Explain our website


---

### Routes *****

- **'/'** - An index hero page with a call to action, navigation and footer
- **'/gallery'** - A gallery page that also includes a random drink option, page pagination, and search.
- **'/gallery/:name'** - Getting a detailed page for one of the drink recipes by name
- **'/gallery?random=true'** - A page generated for one random drink recipe
- **'/gallery?search=drink_name'** - Redirects to **/gallery/:name**
- **'/login'** - A fully functional login that uses bcrypt and postman to authenticate the user. Upon successful login the user is redirected back to the homepage, with logout being displayed as an option in the navbar. Invalid user/password messages appear if the wrong credentials are provided.
- **'/register'** - A registration or subscription page. Any registered user can then log in with the email and password. A user can choose to subscribe instead. In both cases, the user will be given a success/failure message.
- **'/subscribe'** - Adds the same functionality as the subscribe option in the register page, but added for the assignment requirements
- **'/admin'** - Lists all the subscribed users and emails.

#### API's ****

- **'/api/v0/gallery'** - Serves drinks objects with enabled pagination
- **'/api/v0/subscribers'** - Serves subscriber object list
- **'/api/v0/members'** - Serves the team member objects

## Fancy Feature *****

- A login with authentication is done in the '/login' route.
- Need to register first in '/register'
- Invalid User name and password get rejected
- A successful login is met with a custom greeting on the homepage.
- The passport authentication for the special feature is done in /lib/auth
- The bcrypt password hashing is applied as a method on the UserModel Schema
- express-session and express-flash are incorporated as middlewares in server.js

---

### Dependencies *****


- [dotenv](https://www.npmjs.com/package/dotenv) to load environment variables
- [ejs](https://www.npmjs.com/package/ejs) In order to work with javascript templates to generate dynamic pages
- [express](https://www.npmjs.com/package/express) Framework to handle the server side routing
- [express-flash](https://www.npmjs.com/package/express-flash) Flash Messages for your Express Application
- [express-session](https://www.npmjs.com/package/express-session) Creating a session middleware for login
- [mongoose](https://www.npmjs.com/package/mongoose) Mongoose is a MongoDB object modeling tool designed to work in an asynchronous environment. Mongoose supports both promises and callbacks.


---

### Images *****

- error.jpg image by [alleksana](https://www.pexels.com/@alleksana) from [Pexels](https://www.pexels.com/photo/wood-dirty-writing-abstract-4271933/)

  - [Pexels License](https://www.pexels.com/license/)

- Hero Image [Adam Jaime](https://unsplash.com/@arobj) from [Unsplash](https://unsplash.com/photos/dmkmrNptMpw)
  - [Unsplash License](https://unsplash.com/license)

- l Images by [](https://www.pexels.com/@isabella-mendes-107313)

-Images by [](https://www.pexels.com/@charlotte-may)

-Images by [](https://www.pexels.com/@geraud-pfeiffer)

-pictures from API [](https://www.thecocktaildb.com/api.php)

---

### Icons ********

- [Font Awesome License](https://fontawesome.com/license) Used: chevron left & right, star, GH icons

---

### Content/text *****

- [Google Fonts](https://fonts.google.com/?preview.text_type=custom) used: Monsterrat & Roboto, [Privacy Policy](https://policies.google.com/privacy?hl=en)

# Group Charter

---

## Mysia

- ``Full stack support``
  - Markdown's edition
  - Made group charter
  - Editing images (squoosh)

## James

- ``FrontEnd:``
  - static pages;
  - fancy features;
  - JS endpoints;
  - CSS Styling
  - And +

## Jean Marc

- ``Backend``
  - Mongoose and +


