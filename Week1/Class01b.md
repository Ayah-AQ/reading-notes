#  Express, NPM, TDD, CI/CD

## Reading Questions:

### An introduction to NodeJS and Express

> 1. Explain middleware, answer as though I were a non-technical recruiter.
>> We can think of it as a helpful layer between the server and the application. It allows developers to add functionality to their web applications without directly modifying the core code. It can handle tasks such as authentication, logging, error handling, and more. Middleware makes it easier to manage and organize different parts of the application, enhancing its overall performance and maintainability.<br/>
 2. Express the most popular __ __ ____.<br/>
>> Node web framework<br/>
 3. Express is “unopinionated.” What does that mean?<br/>
 >> This means that Express does not impose strict rules or conventions on how you should structure your application. It provides a minimal set of functionalities and leaves the majority of decisions to the developer.<br/>
 4. What is a module and why is modularity useful to us as developers?<br/>
 >> module is a self-contained unit of code that performs a specific functionality. It can be a file or a collection of files that encapsulate related code, data, and resources.


------------------
### What is NPM?
> 1. What version of npm are you running on your machine?
>> 9.6.6<br/>
2. What command would you type to install a library/package called ‘jshint’ into your node project?
>> npm i jshint

--------------------
### What is TDD?
> 1. Explain why tests are important. Please explain as though I were your non technical elder.
>> Tests are important because they help ensure that software or applications work as intended. Just like how you might check the quality of a product before using it, tests are like quality checks for software. They help identify any issues or problems that might be present, making sure that everything runs smoothly.<br/>
 2. What are three expected benefits of testing
>>1- many teams report significant reductions in defect rates, at the cost of a moderate increase in initial development effort <br/>
>>2- the same teams tend to report that these overheads are more than offset by a reduction in effort in projects’ final phases<br/>
>> 3- although empirical research has so far failed to confirm this, veteran practitioners report that TDD leads to improved design qualities in the code, and more generally a higher degree of “internal” or technical quality, for instance improving the metrics of cohesion and coupling <br/>
3. Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.
>> <strong>Individual pitfalls:</strong> <br/>
 1- Overlooking edge cases: Focusing only on expected scenarios and neglecting unusual inputs or extreme values that can lead to unexpected errors.
 <br/> 2- Lack of test coverage: Failing to sufficiently test all parts of the code, increasing the risk of undiscovered bugs and reducing the effectiveness of testing.

>> <strong>Team pitfalls:</strong><br/>
 1- Poor communication and coordination: Inconsistent or incomplete testing due to a lack of proper communication and coordination among team members, resulting in gaps in test coverage and wasted resources. <br/>
 2-Ignoring test maintenance: Neglecting to update and maintain tests over time, leading to outdated or irrelevant tests that can produce false positives or negatives, undermining their reliability and usefulness.
-----------------
### CI/CD
> 1. What are three benefits of Continuous Integration?
>>

> 2. What is the difference between Continuos Delivery and Continuous Deployment?
>>

> 3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background
>>
