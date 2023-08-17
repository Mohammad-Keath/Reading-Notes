
- ## Component Lifecycle useEffect Hook   .  [<sub>    Reference </sub>](https://react.dev/reference/react/useEffect#reference)
  1. #### What is the main intended use case for the useEffect hook?
     - Connecting to an external system 
     - Controlling a non-React widget
     - Wrapping Effects in custom Hooks 
     - Specifying reactive dependencies 
     - Updating state based on previous state from an Effect 
  2. #### How does the effect’s logic interact with the component?
     - useEffect is a Hook, so you can only call it at the top level of your component or your own Hooks. You can’t call it inside loops or conditions. If you need that, extract a new component and move the state into it.
  3. #### What is the importance of the return value from the effect’s logic function?
     - when we call return inside useEffect that means this logic will applied when unmount
  