[Return to the Table of Contents](README.md)

# React Lifecycle

1. Based off the diagram, what happens first, the "render" or the "componentDidMount"?
   1. ComponentDidMount
2. What is the very first thing to happen in the lifecycle of React?
   1. When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, staticgetDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.
3. Put the following things in the order that they happen:
   * componentDidMount - 4
   * render - 2
   * constructor - 1
   * componentWillUnmount - 5
   * React Updates - 3
4. What does componentDidMount do?

# Additional Resources

* [React Bootstrat Documentation](https://react-bootstrap.github.io)
* [Netlify](https://www.netlify.com)

# Video

* [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)
  1. What types of things can you pass in the props?
     1. You can pass components and state.
  2. What is the big difference between props and state?
     1. Props are handled outside the component
     2. State are handled inside the component
  3. When do we re-render our application?
     1. When we are using a counter, state is there when you need to rerender the application.
  4. What are some examples of things that we could store in state?
     1. State is there when you need to rerender your application.
     2. State is good when used inside of the form.

# Bookmark / Skim

* [React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)
* [React Docs - handling events](https://reactjs.org/docs/handling-events.html)
* [React Tutorial through 'Developer Tools'](https://reactjs.org/tutorial/tutorial.html)
