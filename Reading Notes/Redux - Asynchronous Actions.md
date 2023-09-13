- ## Redux - Asynchronous Actions   .  [<sub>    Reference </sub>](https://redux.js.org/tutorials/fundamentals/part-6-async-logic)
- ### async actions
    1. #### Why use Redux middleware?
        - because the redux function cannot be async it must be sync, so the only way to use async function is by adding a middleware
    2. #### Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.
       - after you adding the reducers and redux index, you have to create two functions first to send to reducer and the other one to fetch the api, and you have to add a middle ware to the redux index to waste some time until the function fetch api
    3. #### How are we accommodating async in our Redux app?
       - after you adding the reducers and redux index, you have to create two functions first to send to reducer and the other one to fetch the api, and you have to add a middle ware to the redux index to waste some time until the function fetch api
- ### thunk middleware
    1. #### Why would you need redux-thunk middleware?
       - because you need to have something that takes sometime to allow the async function to get data
    2. #### Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.
       -  dispatch function
    3. #### Describe how any return value from the inner thunk function will be made available.
       - Any return value from the inner function will be available as the return value of dispatch itself. This is convenient for orchestrating an asynchronous control flow with thunk action creators dispatching each other and returning Promises to wait for each other’s completion

