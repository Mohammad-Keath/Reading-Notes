- ## Application State with Redux   .  [<sub>    Reference </sub>](https://egghead.io/courses/fundamentals-of-redux-course-from-dan-abramov-bd5cc867)
    1. #### What is the first principle of Redux?
      - Single Source of Truth: The application's entire state is stored in a single object, typically called the "store."
    2. #### what is a store and what do we use our reducers for within that store?
        - we usually create our components inside it like reducer , actions and state
    3. #### Name three Redux store methods given to us by createStore and describe their use.
        - getState():method is used to retrieve the current state of the Redux store
        - dispatch(action): used to dispatch actions to the Redux store.
        - subscribe(listener): used to add a change listener to the Redux store.
    4. #### Explain to a non-technical recruiter what combineReducers() does and why it is useful.
        - it is very important when you have a huge project with a lot of states that will be used in more than one component, so you have to make your code clear and easy to read by create more than one reducer and compind them using redux combineReducers
       