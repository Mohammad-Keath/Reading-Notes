
- ## Redux - Additional Topics  .  [<sub>    Reference </sub>](https://redux-toolkit.js.org/introduction/getting-started)
- ### Redux Toolkit (RTK)
    1. #### What concerns are addressed by Redux Toolkit?
        -  includes a powerful data fetching and caching capability that we've dubbed "RTK Query"
    2. #### What does configureStore() do?
       - provide simplified configuration options and good defaults. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension
    3. #### How would I use createSlice()?
       - accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types.
- ### MobX
    1. #### What is Mobx?
       - a simple, scalable and battle tested state management solution.
    2. #### How does MobX make it “impossible” to produce an inconsistent state?
       - by addressing the root issue: Make sure that everything that can be derived from the application state, will be derived. Automatically.
    3. #### How would we build a reactive user interface?
       - MobX will Automatically execute code that solely depends on state. So that our report function updates automatically, just like a chart in a spreadsheet.
