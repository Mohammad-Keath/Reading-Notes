   - ## Authentication  .  [<sub>    Reference </sub>](https://canvas.instructure.com/courses/6888396/assignments/37655857/submissions/91763049)
     - ### Securing Passwords:
        1. #### Explain to a non-technical friend how you would safely hash and store a password.
           - for example if we want to make a special type of food and we dont need others to know how to make it we usually put the ingrediants inside boxes that is named with code that we just know what it means, because if you keep them inside their boxes so when any one see you making it, he will be knowing how to make it

        2. #### What is Bcrypt?
           - it is an algorithms that can make a code that is hard to predict and needs long time to know the original value
        
        3. #### Why might you use something like Bcrypt?
           - we use bcrypt to make our website safer and to protect the users account from hacking as much as we can.

     - ### Basic Auth
        1. #### What is Basic Authentication?
           - it is type of security that brawzers uses that change the username and password to a code using base-64

        2. #### What properties are necessary in the header of a Basic Auth request?
           - it require Authorization: Basic <credentials>
           what we care about is th <credentials> that is a code for the user name and password together and we can uncode it using base64

        3. #### How are username:password in Basic Auth encoded?
            - first we have to put them inside special container like (username:password) then we will call the code encode to make it as one code
    
      - ### OWASP auth cheatsheet 
        1. #### Define the authentication process to a non-technical recruiter.
           - it is the require of intering a specific page, for example if someone needs to enter a wedding party he has to have an invitation letter that allows him to enter,
           so the invitation letter is like the user name and the password, and the wedding party is like the page that you want to enter

        2. #### How should your error messaging respond (both HTTP and HTML)? Why?
           - we usually have 3 types of errors
              1. The user ID or password was incorrect. 
                  - when one of the inputs is wrong
              2. The account does not exist. 
                  - when the username is not exist in the database
              3. The account is locked or disabled.
                  - when the account is being stopped
