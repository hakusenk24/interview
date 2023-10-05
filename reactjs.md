# React Interview Questions & Answers

### Table of Contents

| No. | Questions                                                                                                                                                                                                                        |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     | **Core React**                                                                                                                                                                                                                   |
| 1   | [What is React?](#what-is-react)                                                                                                                                                                                                 |
| 2   | [What is JSX?](#what-is-jsx)                                                                                                                                                                                                     |  |
| 3   | [What are Pure Components?](#what-are-pure-components)                                                                                                                                                                           |
| 4   | [What is state in React?](#what-is-state-in-react)                                                                                                                                                                               |
| 5   | [What are props in React?](#what-are-props-in-react)                                                                                                                                                                             |
| 6  | [What is the difference between state and props?](#what-is-the-difference-between-state-and-props)                                                                                                                               |
| 7  | [Why should we not update the state directly?](#why-should-we-not-update-the-state-directly)                                                                                                                                     |
| 8  | [What is the purpose of callback function as an argument of setState()?](#what-is-the-purpose-of-callback-function-as-an-argument-of-setstate)                                                                                                                                                                                                                     |
| 9  | [What is "key" prop and what is the benefit of using it in arrays of elements?](#what-is-key-prop-and-what-is-the-benefit-of-using-it-in-arrays-of-elements)                                                                     |
| 10  | [What is the use of refs?](#what-is-the-use-of-refs)                                                                                                                                                                             |
| 11  | [How to create refs?](#how-to-create-refs)                                                                                                                                                     |
| 12  | [What is Virtual DOM?](#what-is-virtual-dom)                                                                                                                                                                                     |
| 13  | [How Virtual DOM works?](#how-virtual-dom-works)                                                                                                                                                                                                                                                                                                       |
| 14  | [What are the lifecycle methods of React?](#what-are-the-lifecycle-methods-of-react)                                                                                                                                             |
| 15  | [What are Higher-Order components?](#what-are-higher-order-components)                                                                                                                                                                                                                                                                                   |
| 16  | [What is context?](#what-is-context)                                                                                                                                                                                             |
| 17  | [What is children prop?](#what-is-children-prop)                                                                                                                                                                                 |         |
| 18  | [What is reconciliation?](#what-is-reconciliation)                                                                                                                                                                                                                                                                                                  |
| 19  | [What are fragments?](#what-are-fragments)                                                                                                                                                                        |
| 20  | [What are stateless components?](#what-are-stateless-components)                                                                                                                                                                 |
| 21  | [What are stateful components?](#what-are-stateful-components)                                                                                                                                                                   |
| 22  | [What are the advantages of React?](#what-are-the-advantages-of-react)                                                                                                                                                           |
| 23  | [What are the limitations of React?](#what-are-the-limitations-of-react)                                                                                                                                                         |
| 24  | [What are error boundaries in React v16](#what-are-error-boundaries-in-react-v16)                                                                                                                                                |                                                                                
| 25  | [What is ReactDOMServer?](#what-is-reactdomserver)                                                                                                                                                                               |
| 26  | [How do you memoize a component?](#how-do-you-memoize-a-component)                                                                                                                                                               |
| 27  | [Can you force a component to re-render without calling setState?](#can-you-force-a-component-to-re-render-without-calling-setstate)                                                                                             |                                                          |
| 28  | [How to loop inside JSX?](#how-to-loop-inside-jsx)                                                                                                                                                                               |
| 29  | [What are React Hooks?](#what-are-react-hooks)                                                                                                                                                                               |
| 30  | [Why should use Hooks?](#why-should-use-hooks)                                                                                                                                                                               |
| 31  | [Name some Hook methods](#name-some-hook-methods)                                                                                                                                                                               |
| 32  | [When would you use useMemo?](#when-would-you-use-usememo)                                                                                                                                                                               |
| 33  | [When would you use useCallback?](#when-would-you-use-usecallback)                                                                                                                                                                               |
| 34  | [When would you use useEffect?](#when-would-you-use-useeffect)                                                                                                                                                                               |
| 35  | [When would you use useRef?](#when-would-you-use-useref)                                                                                                                                                                               |
|     | **React Router**                                                                                                                                                                                                                 |
| 1 | [What is React Router?](#what-is-react-router)                                                                                                                                                                                   |
| 2 | [How React Router is different from history library?](#how-react-router-is-different-from-history-library)                                                                                                                       |
| 3 | [What is the purpose of push and replace methods of history?](#what-is-the-purpose-of-push-and-replace-methods-of-history)                                                                                                       |                                                                                                                               |
|     | **React Redux**                                                                                                                                                                                                                  |
| 1 | [What is Flux?](#what-is-flux)                                                                                                                                                                                                   |
| 2 | [What is Redux?](#what-is-redux)                                                                                                                                                                                                 |
| 3 | [How does Redux work?](#how-does-redux-work)                                                                             |
| 157 | [Can I dispatch an action in reducer?](#can-i-dispatch-an-action-in-reducer)                                                                                                                                                     |
| 4 | [What is the difference between React context and React Redux?](#what-is-the-difference-between-react-context-and-react-redux)                                                                                                                                                                                       |
| 5 | [What is redux-saga?](#what-is-redux-saga)                                                                                                                                                                                       |

## Core React

1.  ### What is React?

    React is an **open-source JavaScript library** that is used for building composable user interfaces, especially for single-page applications.

    **[⬆ Back to Top](#table-of-contents)**
    
2.  ### What are the major features of React?

    The major features of React are:

    - Uses **JSX** syntax, a syntax extension of JS that allows developers to write HTML in their JS code.
    - It uses **Virtual DOM** instead of Real DOM considering that Real DOM manipulations are expensive.
    - Supports **server-side rendering** which is useful for Search Engine Optimizations(SEO).
    - Follows **Unidirectional or one-way** data flow or data binding.
    - Uses **reusable/composable** UI components to develop the view.

    **[⬆ Back to Top](#table-of-contents)**

3.  ### What is JSX?

    JSX (JavaScript XML) is a syntax extension for JavaScript, that allows you to write HTML-like code within your JavaScript code

    **[⬆ Back to Top](#table-of-contents)**

4.  ### What are Pure Components?

    Pure components are the components which render the same output for the same state and props.
    **[⬆ Back to Top](#table-of-contents)**

5.  ### What is state in React?

    _State_ of a component is an object that holds some information that may change over the lifetime of the component. The important point is whenever the state object changes, the component re-renders.
    **[⬆ Back to Top](#table-of-contents)**

6.  ### What are props in React?

    _Props_ are inputs to components. They are passed to components from a parent component.
**[⬆ Back to Top](#table-of-contents)**

7. ### What is the difference between state and props?
    `state` is managed by the component itself and can be updated using the `setState()` function. Unlike props, state can be modified by the component and is used to manage the internal state of the component. Changes in the state trigger a re-render of the component and its children.
    `props` (short for "properties") are passed to a component by its parent component and are `read-only`, meaning that they cannot be modified by the component itself.
    
    **[⬆ Back to Top](#table-of-contents)**

8. ### Why should we not update the state directly?

    If you try to update the state directly then it won't re-render the component.

    **[⬆ Back to Top](#table-of-contents)**

9. ### What is the purpose of callback function as an argument of `setState()`?

    The callback function is invoked when setState finished and the component gets rendered.
    **[⬆ Back to Top](#table-of-contents)**


10. ### What is "key" prop and what is the benefit of using it in arrays of elements?

    A `key` is a special attribute you **should** include when mapping over arrays to render data. _Key_ prop helps React identify which items have changed, are added, or are removed.

    Keys should be unique among its siblings.
11. ### What is the use of refs?

    The _ref_ is used to return a reference to the element. They _should be avoided_ in most cases, however, they can be useful when you need a direct access to the DOM element or an instance of a component.

    **[⬆ Back to Top](#table-of-contents)**

12. ### How to create refs?
    Refs_ are created using `React.createRef()` method and attached to React elements via the `ref` attribute
    **[⬆ Back to Top](#table-of-contents)**
13. ### What is Virtual DOM?

    The _Virtual DOM_ (VDOM) is an in-memory representation of _Real DOM_. The representation of a UI is kept in memory and synced with the "real" DOM.

    **[⬆ Back to Top](#table-of-contents)**

14. ### How Virtual DOM works?

    The _Virtual DOM_ works in three simple steps.

    1. Whenever any underlying data changes, the entire UI is re-rendered in Virtual DOM representation.

       ![vdom](images/vdom1.png)

    2. Then the difference between the previous DOM representation and the new one is calculated.

       ![vdom2](images/vdom2.png)

    3. Once the calculations are done, the real DOM will be updated with only the things that have actually changed.

       ![vdom3](images/vdom3.png)

    **[⬆ Back to Top](#table-of-contents)**

15. ### What are the lifecycle methods of React?

    Before React 16.3

    - **componentWillMount:** Executed before rendering and is used for App level configuration in your root component.
    - **componentDidMount:** Executed after first rendering and here all AJAX requests, DOM or state updates, and set up event listeners should occur.
    - **componentWillReceiveProps:** Executed when particular prop updates to trigger state transitions.
    - **shouldComponentUpdate:** Determines if the component will be updated or not. By default it returns `true`. If you are sure that the component doesn't need to render after state or props are updated, you can return false value. It is a great place to improve performance as it allows you to prevent a re-render if component receives new prop.
    - **componentWillUpdate:** Executed before re-rendering the component when there are props & state changes confirmed by `shouldComponentUpdate()` which returns true.
    - **componentDidUpdate:** Mostly it is used to update the DOM in response to prop or state changes.
    - **componentWillUnmount:** It will be used to cancel any outgoing network requests, or remove all event listeners associated with the component.

    React 16.3+

    - **getDerivedStateFromProps:** Invoked right before calling `render()` and is invoked on _every_ render. This exists for rare use cases where you need a derived state. Worth reading [if you need derived state](https://reactjs.org/blog/2018/06/07/you-probably-dont-need-derived-state.html).
    - **componentDidMount:** Executed after first rendering and where all AJAX requests, DOM or state updates, and set up event listeners should occur.
    - **shouldComponentUpdate:** Determines if the component will be updated or not. By default, it returns `true`. If you are sure that the component doesn't need to render after the state or props are updated, you can return a false value. It is a great place to improve performance as it allows you to prevent a re-render if component receives a new prop.
    - **getSnapshotBeforeUpdate:** Executed right before rendered output is committed to the DOM. Any value returned by this will be passed into `componentDidUpdate()`. This is useful to capture information from the DOM i.e. scroll position.
    - **componentDidUpdate:** Mostly it is used to update the DOM in response to prop or state changes. This will not fire if `shouldComponentUpdate()` returns `false`.
    - **componentWillUnmount** It will be used to cancel any outgoing network requests, or remove all event listeners associated with the component.

    **[⬆ Back to Top](#table-of-contents)**

16. ### What are Higher-Order Components?

    A _higher-order component_ (_HOC_) is a function that takes a component and returns a new component.
    
    HOC can be used for many use cases:

    1. Code reuse, logic and bootstrap abstraction.
    2. Render hijacking.
    3. State abstraction and manipulation.

    **[⬆ Back to Top](#table-of-contents)**


17. ### What is context?

    _Context_ provides a way to pass data through the component tree without having to pass props down manually at every level.

    For example, authenticated users, locale preferences, UI themes.
    **[⬆ Back to Top](#table-of-contents)**

18. ### What is children prop?

    _Children_ is a prop (`this.props.children`) that allows you to pass components as data to other components.

    **[⬆ Back to Top](#table-of-contents)**

19. ### What is reconciliation?

    `Reconciliation` is the process through which React updates the Browser DOM and makes React work faster. React use a `diffing algorithm` so that component updates are predictable and faster. React would first calculate the difference between the `real DOM` and the copy of DOM `(Virtual DOM)` when there's an update of components.
    React stores a copy of Browser DOM which is called `Virtual DOM`. When we make changes or add data, React creates a new Virtual DOM and compares it with the previous one. This comparison is done by `Diffing Algorithm`.
    Now React compares the Virtual DOM with Real DOM. It finds out the changed nodes and updates only the changed nodes in Real DOM leaving the rest nodes as it is. This process is called _Reconciliation_.

    **[⬆ Back to Top](#table-of-contents)**

20. ### What are fragments?

    _Fragments_ let you group a list of children without adding extra nodes to the DOM.

    **[⬆ Back to Top](#table-of-contents)**

21. ### What are stateless components?

    Stateless components are a type of component that doesn't have internal state. They just receive data and render content.

    **[⬆ Back to Top](#table-of-contents)**

22. ### What are stateful components?

    Stateful components are a type of component that can maintain and manage their own internal state data.

    **[⬆ Back to Top](#table-of-contents)**
23. ### What are the advantages of React?

    Below are the list of main advantages of React,

    1. Increases the application's performance with _Virtual DOM_.
    2. JSX makes code easy to read and write.
    3. It renders both on client and server side (_SSR_).
    4. Easy to integrate with frameworks (Angular, Backbone) since it is only a view library.
    5. Easy to write unit and integration tests with tools such as Jest.

    **[⬆ Back to Top](#table-of-contents)**

24. ### What are the limitations of React?

    Apart from the advantages, there are few limitations of React too,

    1. React is just a view library, not a full framework.
    2. There is a learning curve for beginners who are new to web development.
    3. Integrating React into a traditional MVC framework requires some additional configuration.
    4. The code complexity increases with inline templating and JSX.
    5. Too many smaller components leading to over engineering or boilerplate.

    **[⬆ Back to Top](#table-of-contents)**

25. ### What are error boundaries in React v16?

    _Error boundaries_ are components that catch JavaScript errors anywhere in their child component tree, log those errors, and display a fallback UI instead of the component tree that crashed.

    **[⬆ Back to Top](#table-of-contents)**

26. ### What is ReactDOMServer?

    The `ReactDOMServer` object enables you to render components to static markup (typically used on node server). This object is mainly used for _server-side rendering_ (SSR).
    **[⬆ Back to Top](#table-of-contents)**

27. ### How do you memoize a component?

   Simply wrap the component using React.memo before you use it.
    **[⬆ Back to Top](#table-of-contents)**

28. ### Can you force a component to re-render without calling setState?

    By calling `forceUpdate()`.

    ```javascript
    component.forceUpdate(callback);
    ```

    **[⬆ Back to Top](#table-of-contents)**

29. ### How to loop inside JSX?

    Using `Array.prototype.map` with ES6 _arrow function_ syntax

    **[⬆ Back to Top](#table-of-contents)**

29. ### What are React Hooks?

    React Hooks are simple JavaScript functions that we can use to isolate the reusable part from a functional component.
    Hooks can be stateful and can manage side-effects.

    **[⬆ Back to Top](#table-of-contents)**

30. ### Why should use Hooks?

    - Enhance component tree readability 
    - Share logic among different components
    - Effectively handle the setup of side effects

    **[⬆ Back to Top](#table-of-contents)**

31. ### Name some Hook methods

    - useState
    - useEffect
    - useLayoutEffect
    - useMemo
    - useCallback

    **[⬆ Back to Top](#table-of-contents)**
    
32. ### When would you use useMemo?

    useMemo is a Hook that allows us to cache the result of a calculation between re-renders.

    **[⬆ Back to Top](#table-of-contents)**                                                                                                                                                                           

33. ### When would you use useCallback?

    useCallback is a Hook that allows us to cache a function definition between re-renders.

    **[⬆ Back to Top](#table-of-contents)**                                                                                                                                                                        
34. ### When would you use useEffect?

    useEffect is a React Hook that allows us to synchronize a component with an external system, such as a browser API or a third-party library.

    **[⬆ Back to Top](#table-of-contents)**

35. ### When would you use useRef?

    useRef is a React Hook that allows us to reference a value that’s not needed for rendering.

    **[⬆ Back to Top](#table-of-contents)**

## React Router
1. ### What is React Router?

    React Router is a popular library for handling client-side routing in React applications. It provides a way to create single-page applications (SPAs) with multiple "pages" that can be navigated without the need for a full page refresh.

**[⬆ Back to Top](#table-of-contents)**

2. ### How React Router is different from history library?

    React Router is a wrapper around the `history` library which handles interaction with the browser's `window.history`.

**[⬆ Back to Top](#table-of-contents)**

3. ### What is the purpose of `push()` and `replace()` methods of `history`?

     A history instance has two methods for navigation purpose.

     1. `push()`
     2. `replace()`

    Let's think of the history as an array of visited locations, `push()` will add a new location to the array and `replace()` will replace the current location in the array with the new one.

**[⬆ Back to Top](#table-of-contents)**

## React Redux

1. ### What is flux?

    Flux is an architectural pattern used in React applications to manage the flow of data and state in a predictable and unidirectional way.

    Unidirectional Data Flow: Flux enforces a unidirectional data flow, which means that data flows in one direction through the application. This helps in maintaining a clear and predictable flow of data and makes debugging and understanding the application easier.

    Components: In a Flux architecture, React components are responsible for rendering the user interface and emitting actions in response to user interactions.

    Actions: Actions are plain JavaScript objects that represent events or user interactions in the application. Components dispatch actions to describe what happened.

    Dispatcher: The Dispatcher is a central hub that receives all actions from components and dispatches them to registered stores.

    Stores: Stores are responsible for managing the application's data and state. They listen for actions dispatched by the Dispatcher and update their data accordingly. Stores are the only entities that can modify their data.

    View-Store Binding: React components can listen to changes in stores and automatically update their views when the data in the store changes. This is often achieved using React's setState or modern state management libraries like Redux, which follows the Flux pattern.

**[⬆ Back to Top](#table-of-contents)**

2. ### What is Redux?

    _Redux_ is a state management library provides a predictable and centralized way to manage the state of your application.

**[⬆ Back to Top](#table-of-contents)**

3. ### How does Redux work?
  The way Redux works is simple. There is a central store that holds the entire state of the application.

  - When the user interacts with the application and performs some actions. Then these actions are dispatched by the dispatcher. This means that when the user do some changes in the application then these actions sent a request to the store. For changing the state of the application.  
  
  - After receiving the request for the action at the store. The store is called the root reducer function to perform an action and provide the next stage of the application. The root reducers perform the task using the divide-conquer. The root reducer divides the task in the smaller reducer function which all together performs the whole change state of the application.
  
  - Then these changes are sent to the middleware to test the actions whether these actions are valid for the store or not. And also perform the necessary changes in the action and then send them to the store.
  
  - When a store gets information about changing the state of the application. Store notifies the changes to the registered listeners that a state change has occurred. Then various parts of the application will be updated as required.

**[⬆ Back to Top](#table-of-contents)**

4. ### What is the difference between React context and React Redux?

     You can use **Context** in your application directly.

     Whereas **Redux** is much more powerful and provides a large number of features that the Context API doesn't provide. Also, React Redux uses context internally but it doesn't expose this fact in the public API.

**[⬆ Back to Top](#table-of-contents)**

5. ### What is redux-saga?

     `redux-saga` is a library that aims to make side effects (asynchronous things like data fetching and impure things like accessing the browser cache) in React/Redux applications easier and better.

     It is available in NPM:

     ```console
     $ npm install --save redux-saga
     ```

**[⬆ Back to Top](#table-of-contents)**
