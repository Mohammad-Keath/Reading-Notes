
- ## Context API .  [<sub>    Reference </sub>](https://canvas.instructure.com/courses/6888396/discussion_topics/18305197/submit)
   - ### Choosing the State Structure
      1. #### Summarize the five principles for structuring state.
         - Group related state. merging simmilar states into a single state variable.
         - Avoid contradictions in state. avoid disagreement
         - Avoid redundant state. If you can calculate some information from the component’s props or its existing state variables during rendering, you should not put that information into that component’s state.
         - Avoid duplication in state. When the same data is duplicated between multiple state variables, or within nested objects, it is difficult to keep them in sync. Reduce duplication when you can.
         - Avoid deeply nested state. Deeply hierarchical state is not very convenient to update. When possible, prefer to structure state in a flat way.
   - ### Passing State Deeply with Context
      1. #### What problem do Contexts aim to solve?
         - Start by passing props. If your components are not trivial, it’s not unusual to pass a dozen props down through a dozen components. It may feel like a slog, but it makes it very clear which components use which data! The person maintaining your code will be glad you’ve made the data flow explicit with props.
      2. #### What is one technique to try before useContext?
         - Passing props is a great way to explicitly pipe data through your UI tree to the components that use it.
      3. #### What hook complements useContext for complex applications?
         - Replace prop drilling with context 
         - 