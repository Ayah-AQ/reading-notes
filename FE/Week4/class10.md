# differences between path parameters and query string parameters.


| Type of Parameter   | Description                                       | Example                             |
|---------------------|---------------------------------------------------|-------------------------------------|
| Path Parameter      | Part of the URL path, specifies a resource       | http://our-site.com/api/v3/stuff/things |
| Query String        | Appended to the URL after a question mark, used  | http://example.com/api/v1/products?category=electronics |
| Parameter           | for filtering, sorting, or additional info.      |                                     |
|                     | Represents key-value pairs separated by "&".     |                                     |

> We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.
>> Our dynamic API is like a super-smart helper for our online store. It understands what you want and brings it to you. Just like asking for things, and it gives you what you asked for. It's like magic for our website!



> Q1: Describe how you would use middleware to implement basic and bearer auth.
>> Middleware is like security guards for our server. 
>> - Basic Authentication Middleware checks your username and password when you sign in. 
>> - Bearer Authentication Middleware checks a special token you get after signing in to make sure you're allowed to access our server.

> Q2: Describe the handshake necessary to implement OAuth.
> OAuth is like a secret handshake between a website and a service (like Google) you use to log in. It ensures you're really you without sharing your password. It's a secure way to prove your identity.

> Q3: Describe how Role-Based Access Control works to a non-technical friend.
>> Role-Based Access Control is like having different passes at a concert. Users have roles (like fan, VIP, or staff), and each role gives access to specific parts of the system. It's like showing the right pass to enter a special area, depending on your role.