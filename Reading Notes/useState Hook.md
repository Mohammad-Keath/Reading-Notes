- ## useState Hook  .  [<sub>    Reference </sub>](https://canvas.instructure.com/courses/6888396/discussion_topics/18305200/submit)
   - ### Thinking in React
      1. #### Summarize the five steps of thinking in react.
        - Step 1: Break the UI into a component hierarchy:
          it is to start with programming, CSS then Design
        - Step 2: Build a static version in React 
          to build the components
        - Step 3: Find the minimal but complete representation of UI state 
          to create simple design to show functionality
        - Step 4: Identify where your state should live 
          Identify every component that renders something based on that state.
        - Step 5: Add inverse data flow 
          you will need to support data flowing the other way: the form components deep in the hierarchy need to update the state
   - ### State: A Component’s Memory
      1. #### What is one reason a local variable isn’t sufficient for managing a React component?
        - Local variables don’t persist between renders. When React renders this component a second time, it renders it from scratch—it doesn’t consider any changes to the local variables.
      2. #### What is the argument to the useState hook, and what are the two parts of its return array?
        - A state variable to retain the data between renders.
        - A state setter function to update the variable and trigger React to render the component again.
      3. #### How can Component A access state from Component B?
        -  it depends on thier relation 
          parent will send information to child using props
          child will send information to parent by importing the function
   