# Component Lifecycle

## useEffect hook

What is the main intended use case for the useEffect hook?

- Use effect is used to connect ot an external system or perform an action outside of the component.  

How does the effect’s logic interact with the component?

- Setup function conatins the logic neede to perform the effect. When the componety is addedto the DOM the setup function will run. after ech rerender the cleanup function provided will run with the original values and setup will run updating the component. When the component is removed to the cleanup function runs again.  

What is the importance of the return value from the effect’s logic function?

- The return value from the function is undefined unless a cleanup function is provided.  
