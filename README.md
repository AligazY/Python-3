# Python-3

As a database you can use any SQL database( postgresql, mysql, sqlite) Database should have at least one Table with name User, and columns: id, login, password, token User Table should contain at least 3 records

#/login

Use as a baseline a code which was provided in a Week 6, Moodle After successful login( if login and password matches with a record in User Table), as response route should return html text: token: and store that token in the User Table If provided login and password does not exist in the User Table, as a response route should return html text: Could not found a user with login:

#/protected

This route should receive as a parameter token value Token value needs to be passed over URL,  e.g. http://127.0.01:5000/protected?token=24230ifdsjfjdsklfj43943ut943 This route should return html text: Hello, token which is provided is correct, if as a parameter RIGHT token value is passed This route should return html text: Hello, Could not verify the token, if as a parameter WRONG token value is passed

