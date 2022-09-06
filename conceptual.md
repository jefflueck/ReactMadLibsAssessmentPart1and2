### Conceptual Exercise

Answer the following questions below:

- What is React? When and why would you use it?

  React is a Javascript front-end framework. It allows us to build single page applications that do not refresh every time the use interacts with the page.

- What is Babel?

  Babel is a Javascript complier that takes our React components and JSX and turns it into Javascript that the browser can understand.

- What is JSX?

  JSX is JavaScript Extended Notation. It is a way we can write HTML in our JS files.

- How is a Component created in React?

  A component is a class or function that returns JSX. It is a way to create reusable pieces of code.

- What are some difference between state and props?

  Props are can be passed down from parent components to child components and are immutable. State is mutable and can be changed by the component.

- What does "downward data flow" refer to in React?

  passing data or functions down through props from a parent to a child component.

- What is a controlled component?

  A controlled component takes its current value through props and notifies changes through callbacks like onChange.

- What is an uncontrolled component?

  An uncontrolled component is a component that stores its own state.

- What is the purpose of the `key` prop when rendering a list of components?

  The key prop is used to identify each component in a list. It is used by React to keep track of which components have changed, are added, or are removed.

- Why is using an array index a poor choice for a `key` prop when rendering a list of components?

  Using an array index as a key prop can cause problems if the order of the list changes. It can also cause problems if items are added or removed from the list.

- Describe useEffect. What use cases is it used for in React components?

  useEffect is a hook that allows us to perform side effects in a functional component. We can use it for things like fetching data from an API, setting up a subscription, or manually changing the DOM.

- What does useRef do? Does a change to a ref value cause a rerender of a component?

  useRef returns a mutable ref object whose .current property is initialized to the passed argument (initialValue). The returned object will persist for the full lifetime of the component. A change to a ref value does not cause a rerender of a component.

- When would you use a ref? When wouldn't you use one?

  You would use a ref when you need to access a DOM node or an instance of a component. You would not use a ref when you need to store a value that will cause a rerender of a component.

- What is a custom hook in React? When would you want to write one?

  Building your own hook allows you to extract component logic into reusable functions.

  You would want to write a custom hook when you need to do the same operation, like an API call, across multiple components.
