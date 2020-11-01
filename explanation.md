Server.js is where you build your server and connect everything together. 
package.json shows all the files and the versions we installed using npm install.

Config Folder which holds the middleware. Middleware holds the data used to authentic and makes sure the user made a lonin and user. If the user tried accessing this without logging in it would redirect them.

Config.json file used to access mysql database and your schemas. You have your info such as password and username for the sql.
User.js helps create new user and password. Protects their password.

Passport.js looks at the data and compare it to the database to make sure its correct. Makes sure the username and password are correct. Send the user messages if the info is incorrect.

models folders which contains model files which holds and stores data. The index holds the sequelize and filter. User file holds which exports the functions which makes sure the user and password is correct.

Public folder will hold all the html and will have what the user will see when the user goes to the app. The style.css file provides the styling for all the html. 

Js folder has has all the js files for each html file to make it function such the login button.

api routes will have all the routes such as what will happen when you click on log in or logout it will have the route for eaxh button which is on the html page.
Html route connects to middleware and redirects the member to login if they aren't logged in. Basically authenticates the user.

