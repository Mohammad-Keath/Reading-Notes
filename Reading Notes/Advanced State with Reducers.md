
- ## Advanced State with Reducers   .  [<sub>    Reference </sub>](https://react.dev/learn/extracting-state-logic-into-a-reducer)
  1. #### What is the motivation for adding a reducer?
     - As your components grow in complexity, it can get harder to see at a glance all the different ways in which a component’s state gets updated.
  2. #### What are actions in the context of a reducer? How are they different than setting state directly?
     - Move from setting state to dispatching actions.
     - Write a reducer function.
     - Use the reducer from your component.
  3. #### What common list operation is useReduce named for, and why?
     - handleAddTask(text) is called when the user presses “Add”.
     - handleChangeTask(task) is called when the user toggles a task or presses “Save”.
     - handleDeleteTask(taskId) is called when the user presses “Delete”.
  4. #### When should you switch from useState to useReducer?
     - Components with many state updates spread across many event handlers can get overwhelming. For these cases, you can consolidate all the state update logic outside your component in a single function, called a reducer.