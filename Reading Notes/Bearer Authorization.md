- ## Bearer Authorization  .  [<sub>    Reference </sub>](https://canvas.instructure.com/courses/6888396/discussion_topics/18305212/submit)
   - ### Intro to JWT
      1. #### What is a JSON Web Token (JWT)?
        - self-contained way of securety transition between the same website routes without needing to sign in every time
      2. #### When should we use JSON Web Tokens?
        - we should use it when we build a website that contains privet information and it needs to sign in to show the details and usually its more than one route
      3. #### Claims are expected in which structural component of a JWT?
        - it is expected in Payload whithin there three types of it (Registered claims,Public claims,Private claims)
   - ### Are JWTs Secure?
      1. #### If I get a JWT and I can decode the payload, how can we call that secure?
        - of course you can decode it but that because you know the privet key of it so that what others dont know
      2. #### If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
        - they both must know the encoded code and the type of dependecies that the sender use and of course the secret (Hash(payload + secret)) 
      3. #### Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
        - it is simply like when you send a closed box to your friend that just you and him have the key of it
   - ### JWTs Explained
      1. #### Why use JWT?
        - of couse there are alot of other dependencies but this one offers a lot of choices for authentication and authorization 
      2. #### JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
        - it means that it is easy to use and no need to other dependencies and it carrying securely
      3. #### What are the three components (the structure) of a JWT signature?
        - Header:  contains metadata about the JWT
        - Payload: contains the actual data
        - Signature: The signature is created by mixing header with payload

