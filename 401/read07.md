# Read07 Summary

![jwt](https://miro.medium.com/max/2000/1*u3a-5xZDeudKrFGcxHzLew.png)

JWT or JSON Web Token is a network standard that creates data with an otional encryption in which a token can be either private or public key. One of the best things about a JWT is that it is cryptographically signed, & can be signed in a number of ways such as using HMAC shared secret and RSA public/private key pairs. When a token is issued by a third-party, that third party can use a private key to sign the claims of the token, & then any third-party can verify that the claims were issued by a safe third-party by validating the signature using a public key.

**When should you use JSON Web Tokens?**

Authorization: This is the most common scenario for using JWT. Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token. Single Sign On is a feature that widely uses JWT nowadays, because of its small overhead and its ability to be easily used across different domains.

Information Exchange: JSON Web Tokens are a good way of securely transmitting information between parties. Because JWTs can be signed—for example, using public/private key pairs—you can be sure the senders are who they say they are. Additionally, as the signature is calculated using the header and the payload, you can also verify that the content hasn't been tampered with.

**How does JWT work ?**

The purpose of using JWT is not to hide data but to ensure the authenticity of the data. JWT is signed & encoded, not encrypted because it is a token based stateless authentication mechanism. Since it is a client-side based stateless session, the server doesn’t have to completely rely on the database to save session information


**Are JWTs' secure ?**

When it comes to security, JWT is not secure like the HTTP because they are not encrypted so anyone able to perform a man-in-the-middle attack and sniff the JWT now has your authentication credentials. This is made easier because the MITM attack only needs to be completed on the connection between the server & the client.