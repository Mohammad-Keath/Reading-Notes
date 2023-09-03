- ## API Integration
 - ### Review API Server Build
      1. #### Explain the different between a query string parameter and a path parameter.
         - Query string parameters are appended to the end of a URL using a question mark (?) followed by key-value pairs separated by ampersands (&). 
         - Path parameters are part of the URL path itself and are denoted by placeholders enclosed in curly braces {} or nothing
      2. #### What would our API URL with a path id parameter be given the following information:
       #### Domain: http://our-site.com
       #### v3
       #### model name: stuff
       #### id: things
         - www.our-site.com/v3/stuff/things
      3. #### We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.
         - first we will get the information from the bachend as a JSON 
         - Second we will store the information inside our frontend
         - then we will use these information to fill our frontend
   - ### Review Auth Server Build
      1. #### Describe how you would use middleware to implement basic and bearer auth.
         - in basic we will check if the login info are exist in the data base and are correct to let the user signin
         - in bearer we will check if there is a token and if the info inside the token are corrent and to know the user of that token
      2. #### Describe the handshake necessary to implement OAuth.
         -  create/update a local user account in our database, and return an object with a re-authentication/bearer token and the user object
      3. #### Describe how Role Based Access Control works to a non-technical friend.
         - if you are a student inside a school and you join the LMS of that school so you will not be able to delete your course or to put your marks, So that is simply the based access control so according to your role you will be able to do things