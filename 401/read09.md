# Read09 Summary

RBAC is role-based, so depending on your role in the organization, you will have different access permissions. This is determined by an administrator, who sets the parameters of what access a role should have, along with which users are assigned which roles. For instance, some users may be assigned to a role where they can write and edit particular files, whereas other users may be in a role restricted to reading files but not editing them.

User Roles are permission sets that control access to areas and features within the Professional Archive Platform. Each User account requires a Role assignment.

JWT or JSON Web Token is a network standard that creates data with an otional encryption in which a token can be either private or public key. One of the best things about a JWT is that it is cryptographically signed, & can be signed in a number of ways such as using HMAC shared secret and RSA public/private key pairs

**What header(s) are used in authentication and authorization?**

Basic authentication & bearer token


**What is safe to put into a JWT?**

To secure the JWT, it should be put into the HTTP cookie

**How are JWTs validated?**

Anyone in possession of JWT can decode it and see the content. JWT tokens are digitally signed (the signature part) using the payload content and a secret key. In order to change the content, the secret key is required to generate the signature again, otherwise, the signature will be invalid. When a token is posted to the server, it must be validated to check if anyone has tempered the token or not. Lack of proper validation can cause serious security issues and here we will see how to properly validate a JWT. In order to validate a JWT, you must know the content of JWT.

**Which 3 things had you heard about previously and now have better clarity on?**

JWT, ACL

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

Everything

**What are you most excited about trying to implement or see how it works?**

Everything