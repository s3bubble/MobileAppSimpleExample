# Simple API Example - Build Mobile & Smart TV Apps

This is a very simple app to demonstrate how to use the Theme API to create mobile apps.

### API Calls

All the standard wp rest api calls are included by default

-   Theme specific calls
    -   /wp-json/wp/v2/content // Gets the theme channel content
    -   /wp-json/app/v1/terms // Gets the theme terms to be used for menus
    -   /wp-json/wp/v2/content?browse={id} // Gets content for a term based on term id
    -   /wp-json/app/v1/access // Checks if a user can access a video requires AUTHENTICATION
    -   /wp-json/app/v1/register // Registers a new user
    -   /wp-json/jwt-auth/v1/token // AUTHENTICATES a user based on username and password and returns a JWT token

##### Run the code

You dont need anything special installed to run this code simply replace the global url with your theme demo or live theme and open the html file in a browser.

### Video Tutorial
