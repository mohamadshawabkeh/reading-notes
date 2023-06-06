# Review: ES6 Classes

1. Classes are a template for creating ____.

Ans: objects

2. Can a class declaration be hoisted?

Ans : No, class declarations cannot be hoisted in JavaScript.

3. How would you describe a constructor and contextual “this” to a non-technical friend?

Ans: A constructor is a special function that creates and initializes objects, while the contextual "this" refers to the current object being manipulated or accessed within the constructor or method.

# Using Express Routing

1. Within Express, what does routing refer to?

Ans:routing refers to the process of defining endpoints or routes that handle incoming requests and determine how the server should respond to those requests.

2. What is the difference between a route path and a route method?

Ans:The route path in Express defines the URL pattern of an endpoint, while the route method specifies the HTTP method associated with that endpoint. (Methods like get,post,put,...)

3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

Ans: It is appropriate to add (next) as a parameter to a route handler in Express when you want to pass control to the next middleware function, and if (next) has been passed to your middleware as a parameter, you must call it to pass control to the next middleware function or route handler.

# Express Routing

1. What is an Express Router?

Ans: An Express Router is a middleware that allows you to organize and modularize your routes by grouping related routes together, providing a way to create separate sets of routes that can be mounted and used within an Express application.

2. By what mean do we initialize express.Router() in an express server?

Ans: We initialize express.Router() by creating an instance of it using const router = express.Router(), which returns a new Router object that we can use to define our routes.

3. What do we use route middleware for?

Ans: Route middleware in Express is used to perform operations on the incoming request or response objects, modify them, or execute additional logic before or after the route handler is invoked, providing a way to add custom functionality to specific routes.


 ### return to [Main Read Me File](./README.md)