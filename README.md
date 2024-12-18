**Node.js HTTP Server with Routing and Lodash Integration**

This project demonstrates a simple HTTP server in Node.js with basic routing, integration of the Lodash library, and file rendering for HTML views. The server handles requests, serves different HTML pages, and showcases a redirect functionality.

**Features**

Handles basic HTTP routes:

/ - Serves the home page.

/about - Serves the about page.

/about-me - Redirects to /about.

Any other route - Serves a custom 404 page.

Uses the Lodash library to:

Generate a random number between 0 and 20.

Demonstrate the _.once method to ensure a function is executed only once.

Renders HTML files located in the views directory.

**Prerequisites**

Node.js installed on your machine.

npm (Node Package Manager).


**Dependencies**

http: Core Node.js module to create the server.

fs: Core Node.js module to read files.

lodash: Third-party utility library for additional functionality.

**Routing Logic**

The server inspects req.url to determine the requested route.

Routes:

/ and /about serve respective HTML pages.

/about-me redirects to /about with a 301 status code.

Any unhandled route serves 404.html with a 404 status code.

**Lodash Integration**

_.random: Generates a random number between 0 and 20 and logs it to the console.

_.once: Ensures the greet function is only executed once, even when called multiple times.
