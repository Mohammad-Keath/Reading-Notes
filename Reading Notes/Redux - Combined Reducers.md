- ## Redux - Combined Reducers  .  [<sub>    Reference </sub>](https://canvas.instructure.com/courses/6888396/discussion_topics/18305192/submit)
- ### Multiple Reducers Example
    1. #### Why create multiple reducers?
        - It makes your code clearer and more organized, and in some cases you have only one way to resolve some problems and it will be by multiple reducers
    2. #### How would you combine multiple reducers?
       - inside the index by adding the reducers inside the combineReducers object
    3. #### How will you manage state as an immutable object? why?
       - Use Object Spread (for Objects) and Array Spread (for Arrays)
       - Avoid Direct Mutation
       - Deep Cloning
- ### Redux Docs: Using Combined Reducers
    1. #### combineReducers is a utility function to simplify the most common use case when writing ___ _____ .
       - slice reducer
    2. #### Explain how combineReducers assembles the new state tree.
       - it takes an object full of slice reducer functions, and creates a function that outputs a corresponding state object with the same keys. 
    3. #### How would you define initial state in an app using combineReducers?
       - it is the initial blocks of the states that can determine how the project works and how must the state be
- ### Redux Docs: Combined Reducer Syntax
    7. #### Why will you want to split your reducing functions as your app becomes more complex?
       - It makes your code clearer and more organized, and in some cases you have only one way to resolve some problems and it will be by multiple reducers
    8. #### The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.
       -  combineReducers , redux
       
    9. #### What is a popular convention when naming reducers?
       - state object from the child reducers manually and write a root reducing function explicitly

