A basic web application setup kit with Flask, Postgres, jQuery,  Backbone, Bootstrap, and Underscore
----------------------------------------------------------------------------------------------------

> NOTE: Made for development use, not efficient for pushing to production

### Running the server
```
$ python app.py // Runs the server
```

### Flask
- Basic flask server that serves HTML templates and can access Postgres database
- Can easily serve HTML that uses Backbone and Underscore to template pages for more customizable views

### Postgres
- Link to your database when developing
- Don't forget to install psycopg2 and use this library for making SQL queries to the database

### LESS
- Less is not precompiled so you must include less.min.js on all pages (just like including other requirements such as Backbone, Underscore, jQuery, and Bootstrap) and then pass in your less files as stylesheets so that it can compile them at runtime

### Requirements in HTML
- Make sure requirements stay in the order they are in the `hello.html` test template because each subsequent library usually requires the one above it
