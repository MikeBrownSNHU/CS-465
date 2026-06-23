# CS 465 Portfolio Reflection and README
Mike Brown 06/22/2026

## Architecture

In this course I worked with two different types of frontend development. The customer side of the site used Express, HTML, Bootstrap, and JavaScript. These pages were rendered by the server and sent to the browser when requested.

The admin side was built using Angular as a Single-Page Application (SPA). Instead of loading a new page every time a user clicks something, Angular updates the content on the page without a full refresh. This made the application feel faster and gave me experience working with a more modern web application structure.

MongoDB was used as the backend database because it works well with JavaScript applications. Since data is stored in a document format, it was easy to move information between the database, API, and frontend. The flexibility of MongoDB also made it easier to add and update data as the project grew.

## Functionality

JSON and JavaScript sound similar, but they serve different purposes. JavaScript is the programming language used to create the functionality of the application. JSON is simply a way to organize and transfer data. Throughout this project, JSON was used to send information between the frontend, backend, and database.

One example of refactoring was when we moved functionality into the REST API instead of keeping everything in the server-rendered pages. This helped separate responsibilities and made the application easier to maintain. We also used Angular components that could be reused in multiple places instead of writing the same code repeatedly.

Reusable components save time and make updates easier. If something needs to change, it can usually be updated in one place instead of several. They also help keep the look and behavior of the application consistent.

## Testing

Testing was a big part of making sure everything worked correctly. I tested API endpoints to verify that data could be retrieved, added, updated, and deleted from the database. This included working with GET, POST, PUT, and DELETE requests.

Endpoints are the locations where the frontend communicates with the backend. If an endpoint is not configured correctly, the application will not be able to send or receive data properly. During development I ran into issues with routes, package installations, and API connections. Most of the time the fixes ended up being small mistakes, but finding them taught me a lot about troubleshooting.

Security became important once authentication was added. Using JWT tokens helped protect the admin portion of the application. Testing security involved making sure authorized users could access protected pages while unauthorized users could not.

## Reflection

This course gave me a much better understanding of how a full stack application is built from start to finish. Before this class, I had very little experience with web development frameworks like Angular or working with databases such as MongoDB.

One of the biggest things I learned was how all the pieces work together. The frontend, backend, database, and API all depend on each other, and seeing that connection through a hands-on project made the concepts easier to understand.

I also learned a lot about troubleshooting. There were several times where a missing package, incorrect route, or simple configuration issue caused problems. Working through those issues helped build confidence and showed me that debugging is just as important as writing code.

As someone who works in engineering and automation, I think these skills will help me better understand software projects and communicate with development teams. This course also moved me closer to my goal of expanding my software development knowledge and becoming more well-rounded technically.

Overall, building a complete application from the customer website all the way to the secured admin portal was probably the most valuable part of the course. It was rewarding to see everything come together and actually function as a complete system.
