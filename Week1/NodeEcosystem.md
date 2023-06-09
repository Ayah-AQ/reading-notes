# Node Ecosystem

## Reading Questions:

> 1. How would you describe Node to a non-technical friend?
>> Node.js is a platform that enables developers to use JavaScript for creating server-side applications. It operates independently of web browsers, resulting in high efficiency and speed. One of its key advantages is the ability to share code between the client and server sides of a web application.


> 2. What does it mean that Node is a JavaScript runtime?
 >> It means that Node.js provides an environment in which JavaScript code can be run outside of a web browser.


 > 3. What is Node used for?
>> Node.js is utilized for various purposes, including:
>> 1. web application development
>> 2. real-time interactions
>> 3. API development
>> 4. command-line tools, and more
------------




## Additional Questions
> Looking ahead at this module’s course schedule, What do you look forward to learning?
>> * React - Cookies, Local Storage Login and Auth components
>> * React Native
>> *  Express, NPM, TDD, CI/CD
>> * and every new informations

> What are your learning goals after reading and reviewing the class README?
>> The learning goals include:
>> * Setup a Node.js Package using npm
>> * Create CommonJS modules
>> * Create a simple express server
>> * See passing tests via CI using GitHub actions (Continuous Integration)
>> * Deploy to the cloud using CD (Continuous Deployment)
>>> **Through these objectives, we should gain the knowledge and skills needed to develop applications using Node.js ecosystem, implement Test-Driven Development(TDD) practices, and automate testing and deployment processes using CI/CD.**

------------

# Things I want to know more about
nothing for now 

------------------
# Things to remember 

If one module exports a function or an object …

```ruby
 ## person.js
const person = {};

person.walk = function() {
  return 'walking';
}

module.exports = person;
```

Another module can import and use that function or object
 ```ruby
const human = require('./person.js'))
console.log( human.walk() );  ## prints 'walking'
```