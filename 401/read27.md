# Read27 Summary

![hooks](https://i.ytimg.com/vi/LlvBzyy-558/hqdefault.jpg)

React Hooks are a way for your function components to “hook” into React’s lifecycle & state which means they let you use state and other React features without writing a class. **useState** is a Hook that lets you add React state to function components. If you declare a state variable we simply write something like this:

```
// declaring a state variable using the class

class Example extends React.Component {
  constructor(props) {
    super(props);
    this.state = {
      count: 0
    };
  }
```

```
// declaring the state variable using the useState hook

import React, { useState } from 'react';

function Example() {
  // Declare a new state variable, which we'll call "count"
  const [count, setCount] = useState(0);
```

```
// using the state hooks

import React, { useState } from 'react';

function Example() {
  // Declare a new state variable, which we'll call "count"
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>You clicked {count} times</p>
      <button onClick={() => setCount(count + 1)}>
        Click me
      </button>
    </div>
  );
}
```

![hooks1](https://miro.medium.com/max/2382/1*8Uqq6mfgvApdH2LzuXVdUg.png)

A class component can have state, and it could be manipulated using lifecycle methods such as constructor, componentDidMount and such. However, functional component only accepts props from its parent, and renders accordingly. It wouldn’t keep internal state value, that would be persistent through renders, but rather renders according to whatever passed through props.

## Reading & updating states

When it comes to reading states, we normally as developers we write something like this:

```
// reading states the normal way
  <p>You clicked {this.state.count} times</p>

  // reading states using the hook method
    <p>You clicked {count} times</p>
```

Using the hook states allows you to reduce more codes & work & more than that its much easier to deal with especially for exporting purposes. Here's how updating states should look like:

```
// updating states the normal way

  <button onClick={() => this.setState({ count: this.state.count + 1 })}>
    Click me
  </button>

  // updating states using the hook method

  <button onClick={() => setCount(count + 1)}>
    Click me
  </button>
```

![useeffect](https://ihatetomatoes.net/wp-content/uploads/2020/05/02-react-hook-useEffect.png)

The Effect Hook, useEffect, adds the ability to perform side effects from a function component. It serves the same purpose as componentDidMount, componentDidUpdate, and componentWillUnmount in React classes, but unified into a single API. When you call useEffect, you’re telling React to run your “effect” function after flushing changes to the DOM. Effects are declared inside the component so they have access to its props and state. By default, React runs the effects after every render — including the first render. Effects may also optionally specify how to “clean up” after them by returning a function