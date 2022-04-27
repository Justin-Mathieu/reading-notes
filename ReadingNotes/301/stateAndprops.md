# React Reading Notes

## React lifecycle

1. Based on the diagram the render shpuld happen before the componentDidMount.  
2. In the mountingphsse othe firsts thing to happen ids the constructor.

3. 

- Constructor  
- Render  
- React updates
- ComponentDidUpdate  
- ComponentWillUnmount

4. ComponentWillUnmount will remove and destroy the component from the dom.

## React State Vs Props

1. Props is used to pass things that are not going to change similar to arguments.
2. Props are used when the information being passed down does not change. State isd used when the information is being manipulated in the component.
3. When the state is changed React re-renders the component.
4. Examples of things that could be stored in state are a counter keeping track of clicks or forms.  
