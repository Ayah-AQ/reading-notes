# Class03: Data Modeling

## Reading

### Securing Passwords

> Q1: Explain to a non-technical friend how you would safely hash and store a password.
>>  Safely hashing and storing a password involves converting it into a unique and scrambled string using a special function. We add a random value called a salt to make it even more secure. Then we store this scrambled version in a protected database, never the actual password.

> Q2: What is Bcrypt?
>>Bcrypt is an algorithm designed to securely scramble passwords. It makes it difficult for attackers to guess passwords by slowing down their attempts.

> Q3: Why might you use something like Bcrypt?
>>  We use something like Bcrypt to make it hard for attackers to crack passwords. It slows down their guessing attempts and adds a unique value to each password, making it more secure.

### Basic Auth

> Q1: What is Basic Authentication?
>> Basic Authentication is a method where a username and password are included in an HTTP request to provide authentication.

> Q2: What properties are necessary in the header of a Basic Auth request?
>> The necessary property in the header of a Basic Auth request is the "Authorization" field.

> Q3: How are username:password in Basic Auth encoded?
>> The username and password in Basic Auth are encoded using Base64, which is a way of representing data using ASCII characters.

### OWASP auth cheatsheet

> Q1: Define the authentication process to a non-technical recruiter.
>> Authentication is the process of verifying a user's identity.

> Q2: How should your error messaging respond (both HTTP and HTML)? Why?
>> Clear and helpful error messages are important in both HTTP responses and HTML pages because they improve the user experience, aid troubleshooting, enhance security, and promote accessibility.


> Q3: Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.
>> Bookmark this link for reference on secure authentication practices (OWASP). It helps create more secure applications by following established security guidelines.


### Additional Questions

```

To securely store a password, it is hashed into a unique and scrambled string using a special function, with the addition of a random salt for enhanced security. The scrambled version is stored in a protected database, instead of the actual password. Bcrypt is an algorithm that effectively scrambles passwords, making it difficult for attackers to guess them by slowing down their attempts. Basic Authentication involves including a username and password in an HTTP request, encoded using Base64. Clear and helpful error messages in both HTTP responses and HTML pages are important for improving user experience, troubleshooting, security, and accessibility. Following OWASP's secure authentication guidelines helps develop applications with fewer vulnerabilities throughout their lifecycle.
```