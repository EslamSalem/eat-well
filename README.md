# EatWell - A Dynamic Site
A website I made to practice presenting static and dynamic HTML pages with
server-side tools like NodeJS, ExpressJS, and EJS templates.
# Overview
This is a local website running on a NodeJS server. The requests of
static CSS and JavaScript pages are handled at first without any trouble
by using static() method in ExpressJS. The pages send requests to the server
to travel to another page instead of using anchor tags with relative paths
to the pages in our directory. The requests are handled with ExpressJS.
The recommendations page has a form whose input is passed to the server
and stored in a JSON file to be displayed in the restaurants page later.
We render the HTML pages dynamically with the help of EJS.
We also use EJS to write JavaScript Code in our HTML files to display variable outputs,
reduce redundant code by including a separate EJS file into our code multiple times,
add conditions and loops to dynamically add HTML elements to the page when needed.
# Demo

![eat well](https://github.com/EslamSalem/eat-well/assets/55714424/7cfb974b-5220-4d74-9b78-09c273bbe2d8)
