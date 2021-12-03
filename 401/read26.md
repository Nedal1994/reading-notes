# Read26 Summary

![jsx](https://miro.medium.com/max/1400/1*wQxgEiVsgG0o7ti45WuFTQ.png)

JSX stands for JavaScript XML which makes it easier to write and add HTML in React. It also allows us to write HTML elements in JavaScript and place them in the DOM without any createElement()  and/or appendChild() methods & converts the HTML tags into react elements. JSX is based on an extension to the javascript which is used with the react library in which illustrates how the UI will look like. Like the normal method of using javascript, JSX has the ability to implement functions, expressions, attributes & so on.

```
import React, { Component } from "react";

class Item extends Component {
  render() {
    return (
      <div>
        <h1>Cartable!</h1>
        <button>Increment</button>
      </div>
    );
  }
}

export default Item;
```

 In React we are allowed to use normal JavaScript expressions with JSX. To embed any JavaScript expression in a piece of code written in JSX we will have to wrap that expression in curly braces. JSX expressions become regular JavaScript function calls and evaluate to JavaScript objects. This means that you can use JSX inside of if statements and for loops, assign it to variables, accept it as arguments, and return it from functions

 ```
 const element = <h1>Hello, world</h1>;
 <div id="root"></div>
 ```

  React elements are plain objects, and are cheap to create. React DOM takes care of updating the DOM to match the React elements. In order to render any element into the Browser DOM, we need to have a container or root DOM element. It is almost a convention to have a div element with the id=”root” or id=”app” to be used as the root DOM element. Let’s suppose our index.html file has the following statement inside it

  ```
  function tick() {
  const element = (
    <div>
      <h1>Hello, world!</h1>
      <h2>It is {new Date().toLocaleTimeString()}.</h2>
    </div>
  );
  ReactDOM.render(element, document.getElementById('root'));
}

setInterval(tick, 1000);
```

React Elements are immutable i.e. once an element is created it is impossible to update its children or attribute. Thus, in order to update an element, we must use the render() method several times to update the value over time. Let’s see this in an example.

```
const element = <div tabIndex="0"></div>;
const element = <img src={user.avatarUrl}></img>;
```

JSX allows us to use attributes with the HTML elements just like we do with normal HTML. But instead of the normal naming convention of HTML, JSX uses camelcase convention for attributes. For example, class in HTML becomes className in JSX. The main reason behind this is that some of the attribute names in HTML like ‘class’ are reserved keywords in JavaScripts. So, in order to avoid this problem, JSX uses the camel case naming convention for attributes. We can also use custom attributes in JSX. For custom attributes, the names of such attributes should be prefixed by data-

```
const element = (
  <h1 className="greeting">
    Hello, world!
  </h1>
);

const element = React.createElement(
  'h1',
  {className: 'greeting'},
  'Hello, world!'
);

const element = {
  type: 'h1',
  props: {
    className: 'greeting',
    children: 'Hello, world!'
  }
};
```

React.createElement() performs a few checks to help you write bug-free code but essentially it creates an object like the codes above which are based on the JSX representing objects which look similar to each other. These objects are called “React elements”. You can think of them as descriptions of what you want to see on the screen. React reads these objects and uses them to construct the DOM and keep it up to date.