# todo MVC
### https://todos-crud-mvc.herokuapp.com/


## Overview

This app implements the features of a typical [TodoMVC](https://todomvc.com/)
app, and adds sign in functionality. This app is a traditional web application,
in which all application logic and data persistence is handled on the server.

User interaction is performed via HTML pages and forms, which are rendered via
[EJS](https://ejs.co/) templates and styled with vanilla CSS. Data is stored in
and queried from a [SQLite](https://www.sqlite.org/) database.

After users sign in, a login session is established and maintained between the
server and the browser with a cookie. As authenticated users interact with the
app, creating and editing todo items, the login state is restored by
authenticating the session.

## Tech

-Express js
-Heroku CI
-EJS view Engine
-Passport JS
-SQLite
-CSS

## License

none
