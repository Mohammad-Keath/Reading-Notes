- ## Context API - Behaviors   .  [<sub>    Reference </sub>](https://react.dev/learn/scaling-up-with-reducer-and-context)
  1. #### How do useReducer and useContext work together to simplify state management in a React application? (At least two paragraphs of prose.)
     -  Step 1: Create the context:
       - The useReducer Hook returns the current tasks and the dispatch function that lets you update them
       - To pass them down the tree, you will create two separate contexts:
        TasksContext provides the current list of tasks.
        TasksDispatchContext provides the function that lets components dispatch actions.
     - Step 2: Put state and dispatch into context:
       - Now you can import both contexts in your TaskApp component. Take the tasks and dispatch returned by useReducer()
     - Step 3: Use context anywhere in the tree:
       - any component that needs the task list can read it from the TaskContext
       - To update the task list, any component can read the dispatch function from context and call it