# Read: Class 02

## Readings

### ES6 Classes
> 1. Classes are a template for creating ____.
```
Classes are a template for creating objects
```
> 2. Can a class declaration be hoisted?
```
Yes, class declarations can be hoisted.
However, unlike function declarations, they are not fully initialized and accessible until the declaration is evaluated during runtime. This means that you can declare a class at the beginning of a file, but you can only use it after the declaration.
```
> 3. How would you describe a constructor and contextual “this” to a non-technical friend?
```
A constructor is a special method in a class that creates and sets up objects when you make new instances of the class. It's like an automatic function that runs when you create an object. The "this" keyword refers to the object being created and allows you to work with its properties and methods. It's like a way to refer to yourself within the class.
```
------------
### Using Express Routing
> 1. Within Express, what does routing refer to?
```
Routing in Express refers to how an application handles client requests to specific URLs (endpoints). It involves defining routes based on HTTP methods like GET, POST, etc., and specifying the actions to perform when a request matches a route.
```
> 2. What is the difference between a route path and a route method?

***route path***
```
Is the URL pattern that a route handler matches. It can be a string, pattern, or regular expression, capturing dynamic values using placeholders or route parameters.
```
***route method***
```
 Represents the HTTP method (e.g., GET, POST) a route handler responds to. Express provides methods like app.get() and app.post() for different HTTP methods.


```
> 3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
```
To add next as a parameter in a route handler allows passing control to the next middleware or route handler in the chain. It's useful when you have multiple functions that need to execute in order.
```
----------

### Express Routing

> 1. What is an Express Router?
```
An Express Router is a feature provided by Express framework that helps organize and manage routes in a modular way.
```
> 2. By what mean do we initialize express.Router() in an express server?
```
To initialize an Express Router in an Express server, you simply call express.Router().
```
> 3. What do we use route middleware for?
```
Route middleware is used to perform tasks before or after handling a request. It allows you to modify the request or response, perform authentication, validation, logging, or any other necessary operations.
```