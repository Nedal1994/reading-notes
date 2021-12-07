# Read29 Summary

![usereducer](https://www.c-sharpcorner.com/article/usereducer-hook-in-reactjs-part-one/Images/07.JPG)

The useReducer Hook is similar to the useState Hook. It allows for custom state logic. The reducer function contains your custom state logic and the initialStatecan be a simple value but generally will contain an object. The useReducer Hook returns the current stateand a dispatchmethod. useReducer is used to store and update states, just like the useState Hook. It accepts a reducer function as its first parameter and the initial state as the second. useReducer returns an array that holds the current state value and a dispatch function, to which you can pass an action and later invoke. This is similar to the pattern Redux uses but with a few differences.

```
const initialState = {count: 0};

function reducer(state, action) {
  switch (action.type) {
    case 'increment':
      return {count: state.count + 1};
    case 'decrement':
      return {count: state.count - 1};
    default:
      throw new Error();
  }
}

function Counter() {
  const [state, dispatch] = useReducer(reducer, initialState);
  return (
    <>
      Count: {state.count}
      <button onClick={() => dispatch({type: 'decrement'})}>-</button>
      <button onClick={() => dispatch({type: 'increment'})}>+</button>
    </>
  );
}
```

useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks. There are two different ways to initialize useReducer state. You may choose either one depending on the use case. The simplest way is to pass the initial state as a second argument