A basic web application setup kit with Flask, Postgres, jQuery,  Backbone, Bootstrap, and Underscore
----------------------------------------------------------------------------------------------------

> NOTE: Made for development use, not efficient for pushing to production

### Flask
- Basic flask server that serves html templates and can access Postgres database
- Can easily serve html that uses backbone and underscore to template pages for more customizable views

### Postgres
- Link to your database when developing
- Don't forget to install psycopg2 and use this library for making SQL queries to the database

### LESS
- Less is not precompiled so you must include less.min.js on all pages(just like other requirements) and then pass in your less files as stylesheets so that it can compile them at runtime
