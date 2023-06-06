- ## Express REST API   .  [<sub>    Reference </sub>](https://canvas.instructure.com/courses/6888396/discussion_topics/18305215/submit)
    1. #### Classes are a template for creating
        - Object
    2. #### Can a class declaration be hoisted?
       - No in JS it can't but for other languages like Java yes
    3. #### How would you describe a constructor and contextual “this” to a non-technical friend?
       - constructor is a method to create an object inside class, we can refer to it as a class.
       - this :  we can use it inside the constructor after using super and we use it to refer to the value of mentioned one
    4. #### Within Express, what does routing refer to?
       - it is refer to the URL route that will show us specific website, and use it to decrease area of typing
    5. #### What is the difference between a route path and a route method?
       - the route path : is the part of URL after the / after domain and it will route you to specific website
       - the route method: is the method that the browzer or any program will open the URL with like (get,put,....)
    6. #### When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
       - we use next when we use middleware in order to move to the next middleware or to the response thing, and we usually use it to add or change something when we use this route
    7. #### What is an Express Router?
       - It is a simple way of routing by refering one function or more to each routing with specific method
    8. #### By what mean do we initialize express.Router() in an express server?
       - by requiring it then add it to a variable in order to use it easier
    9. #### What do we use route middleware for?
       - we use it to do specific things like adding custom logic, perform authentication, validation, error handling before we reach by next.
