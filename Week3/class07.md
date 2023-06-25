# Class03: Data Modeling

## Reading

### Intro to JWT

> Q1: What is a JSON Web Token (JWT)?
>> A JSON Web Token (JWT) is a secure way to transmit information between parties using a compact JSON object. It consists of three parts: header, payload, and signature.

> Q2: When should we use JSON Web Tokens?
>> We should use JSON Web Tokens in scenarios where need secure authorization or want to exchange information securely between parties. JWTs are commonly used for authentication, authorization, and information sharing.

> Q3: Claims are expected in which structural component of a JWT?
>> Claims are expected in the payload component of a JWT. The payload contains statements about an entity and additional data. There are registered claims (predefined), public claims (custom but defined in a standard way), and private claims (custom for specific parties).

### Are JWTs Secure?

> Q1: If I get a JWT and I can decode the payload, how can we call that secure?
>> Just being able to decode the payload of a JWT doesn't automatically make it secure. Security depends on how well the secret key used to sign the token is protected.


> Q2: If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
>> When sending a JWT, both the sender and receiver need to know the secret key. It's added to the signature part of the JWT and helps ensure its integrity.

> Q3: Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
>> To securely send concatenated content and a secret to a non-technical recruiter, take these steps: Share the secret through a secure method, explain how to receive the content securely (encrypted email, password-protected files), guide on combining the secret and content, stress confidentiality, and offer support if needed.

# Vedio

## JWTs Explained

> Q1: Why use JWT?
>> JWTs are used to securely transmit information between parties. They are commonly used for authentication and authorization in systems.

> Q2: JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
>> JWTs are like sealed envelopes that contain both the message and a special seal. This makes it easy for my friend to read the message and confirm its authenticity without needing extra tools or instructions.


> Q3: What are the three components (the structure) of a JWT signature?
>> A JWT signature consists of three parts: the header, the payload, and the signature itself. The header specifies the token type and algorithm, the payload carries the data, and the signature verifies the token's integrity.



# Reflection

```
 I learned that JWTs are used for secure communication and can be decoded to access the information they contain. They are compact and self-contained, which means they are easy to send and process. Additionally, the JWT signature consists of three components: the header, payload, and signature itself. This knowledge helps me understand how JWTs work and why they are considered a secure method for transmitting data.
```