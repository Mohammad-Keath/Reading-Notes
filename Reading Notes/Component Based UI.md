
- ## Component Based UI  .  [<sub>    Reference </sub>](https://canvas.instructure.com/courses/6888396/discussion_topics/18305201/submit)
   - ### React Quick Start
      1. #### What are the building blocks of a React app?
        - html file and several js files (index , app and components)
      2. #### What is the difference between an HTML element and a React component?
        - Html element is fixed item that cannot be changed
        - react component can change and when it change it will update without refreshing all other components(vertual DOM)
      3. #### What is JSX and why do we use it?
        - it is the file where we use both HTML and JS together, we use it to easier our coding process 
      4. #### Describe the process of embedding JavaScript expressions in JSX.
        - first you have to declear the variable or the fuction that you need to call before the return, then you need to call it inside return and inside carely brackets.
      5. #### Does React or JSX have any special features for iteration or conditional logic?
        - yes, it has a lot of hooks(useState , useEffect )
      6. #### How does React know to respond to a user’s inputs?
        - it will be saved into a variable and the response will be using a function
      7. #### What word indicates that a React component manages data with a Hook?
        - it starts with use
      8. #### How can two react components share data?
        - it depends on thier relation 
          parent will send information to child using props
          child will send information to parent by importing the function
   - ### Render and Commit
      1. #### What are the three steps of refreshing a React UI?
        - Trigger, Render, Commit
      2. #### How do you trigger updates to a component after the initial render?
        - State update , triggers, render
      3. #### Does React recreate DOM nodes on every rerender?
        - React only changes the DOM nodes if there’s a difference between renders
      4. #### After React has updated the DOM, what still needs to happen before the user sees the change?
        - React commits changes to the DOM 
   