# React Interview Questions & Answers

### Table of Contents

#### Q. What is React?

- React is an `open-source JavaScript library` that is used for building composable user interfaces, especially for single-page applications.


#### Q. What are the major features of React?

- Uses `JSX` syntax, a syntax extension of JS that allows developers to write HTML in their JS code.
- It uses `Virtual DOM` instead of Real DOM considering that Real DOM manipulations are expensive.
- Supports `server-side rendering` which is useful for `Search Engine Optimizations (SEO)`.
- Follows `Unidirectional or one-way` data flow or data binding.
- Uses `reusable/composable` UI components to develop the view.


#### Q. What is JSX?

- `JSX` (JavaScript XML) is a syntax extension for JavaScript, that allows to write `HTML-like code` within the JavaScript code


#### Q. What are Pure Components?

- Pure components are the components which render the same output for the same state and props.


#### Q. What is state in React?

- `State` of a component is an object that holds some information that may change over the lifetime of the component.
	Whenever the state changes, the component re-renders.


#### Q. What are props in React?

- `Props` are inputs to components. They are passed to components from a parent component.


#### Q. What is the difference between state and props?

- `state` is managed by the component itself. State can be modified by the component and trigger a re-render of the component and its children.

- `props` (short for "properties") are passed to a component by its parent component and are `read-only`, meaning that they cannot be modified by the component itself.
    

#### Q. Why should we not update the state directly?

- If you try to update the state directly then it won't re-render the component.


#### Q. What is the purpose of callback function as an argument of `setState()`?

- The callback function is invoked when setState finished and the component gets rendered.


#### Q. What is `key` prop and what is the benefit of using it in arrays of elements?

- A `key` is a special attribute you **should** include when mapping over arrays to render data. `Key` prop helps React identify which items have changed, are 	added, or are removed.

- Keys should be unique among its siblings.


#### Q. What is the use of refs?

- The `ref` is used to access to the DOM element directly to manipulate its data without re-render component.
- `Ref` is created using `React.createRef()` method and attached to React elements via the `ref` attribute


#### Q. What is Virtual DOM?

- The `Virtual DOM` (VDOM) is an in-memory representation of `Real DOM`.


#### Q. How Virtual DOM works?

  The `Virtual DOM` works in three simple steps.

- Whenever any underlying data changes, the entire UI is re-rendered in Virtual DOM representation.

- Then the difference between the previous DOM representation and the new one is calculated.

- Once the calculations are done, the real DOM will be updated with only the things that have actually changed.


#### Q. What are the lifecycle methods of React?

- `componentWillMount`: Executed before first rendering.

- `componentDidMount`: Executed after first rendering.

- `componentWillReceiveProps`: Executed when particular prop updates to trigger state transitions.

- `shouldComponentUpdate`: Determines if the component will be updated or not.

- `componentWillUpdate`: Executed before re-rendering the component when there are props & state changes.

- `componentDidUpdate`: Executed after re-rendering the component.

- `componentWillUnmount`: Executed when the component is destroyed. It will be used to cancel any outgoing network requests, or remove all event listeners associated with the component.


#### Q. What are Higher-Order Components?

- A `higher-order component (HOC)` is a function that takes a component and returns a new component.
    
- `HOC` can be used for many use cases:
	- Code reuse, logic and bootstrap abstraction.
  - Render hijacking.
  - State abstraction and manipulation.


#### Q. What is context?

- `Context` provides a way to pass data through the component tree without having to pass props down manually at every level.
  For example, authenticated users, locale preferences, UI themes.


#### Q. What is children prop?

- `Children` is a prop (`this.props.children`) that allows you to pass components as data to other components.


#### Q. What are fragments?

`Fragments` is used to group a list of children without adding extra nodes to the DOM.


#### Q. What are pure components?

- `Pure components` are a type of component that doesn't have internal state. They just receive data and render content.


#### Q. How do you memoize a component?

- Simply wrap the component using `React.memo` before you use it.


#### Q. What are error boundaries in React v16?

- `Error boundaries` are components that catch JavaScript errors anywhere in their child component tree, log those errors, and display a fallback UI instead of the component tree that crashed.


#### Q. What is ReactDOMServer?

- The `ReactDOMServer` object enables you to render components to static markup (typically used on node server). This object is mainly used for `server-side rendering (SSR)`.


#### Q. Can you force a component to re-render without calling setState?

- By calling `forceUpdate()`.

    ```javascript
    component.forceUpdate(callback);
    ```

#### Q. How to loop inside JSX?

- Using `Array.prototype.map`.


#### Q. What are React Hooks?

- `React Hooks` are simple JavaScript functions that we can use to isolate the reusable part from a functional component.
  `Hooks` can be stateful and can manage side-effects.


#### Q. Why should use Hooks?

- Enhance component tree readability 
- Share logic among different components
- Effectively handle the setup of side effects


#### Q. Name some Hook methods

- useState
- useEffect
- useLayoutEffect
- useMemo
- useCallback

    
#### Q. When would you use useMemo?

- `useMemo` is a Hook that allows us to cache the result of a calculation between re-renders.
	It depends on its dependencies.
          

#### Q. When would you use useCallback?

- `useCallback` is a Hook that allows us to cache a function definition between re-renders.


#### Q. When would you use useEffect?

- `useEffect` is a React Hook that allows us to synchronize a component with an external system, such as a browser API or a third-party library.


#### Q. When would you use useRef?

- `useRef` is a React Hook that allows us to reference a value that’s not needed for rendering.


## React Router

#### Q. What is React Router?

- `React Router` is a popular library for handling `client-side routing` in React applications. It provides a way to create single-page applications (SPAs) with multiple "pages" that can be `navigated` without the need for a full page refresh.


#### Q. How React Router is different from history library?

- `React Router` is a wrapper around the `history` library which handles interaction with the browser's `window.history`.


#### Q. What is the purpose of `push()` and `replace()` methods of `history`?

- Let's think of the history as an array of visited locations, `push()` will add a new location to the array and `replace()` will replace the current location in the array with the new one.


## React Redux

#### Q. What is flux?

- Flux is an architectural pattern used in React applications to manage the flow of data and state in a predictable and unidirectional way.

    `Unidirectional Data Flow`: Flux enforces a unidirectional data flow, which means that data flows in one direction through the application. This helps in maintaining a clear and predictable flow of data and makes debugging and understanding the application easier.

    `Components`: In a Flux architecture, React components are responsible for rendering the user interface and emitting actions in response to user interactions.

    `Actions`: Actions are plain JavaScript objects that represent events or user interactions in the application. Components dispatch actions to describe what happened.

    `Dispatcher`: The Dispatcher is a central hub that receives all actions from components and dispatches them to registered stores.

    `Stores`: Stores are responsible for managing the application's data and state. They listen for actions dispatched by the Dispatcher and update their data accordingly. Stores are the only entities that can modify their data.

    `View-Store Binding`: React components can listen to changes in stores and automatically update their views when the data in the store changes. This is often achieved using React's setState or modern state management libraries like Redux, which follows the Flux pattern.


#### Q. What is Redux?

- `Redux` is a state management library provides a predictable and centralized way to manage the state of your application.


#### Q. How does Redux work?
  The way `Redux` works is simple. There is a central store that holds the entire state of the application.

  - When the user interacts with the application and performs some `actions`. Then these actions are dispatched by the `dispatcher`. This means that when the user do some changes in the application then these `actions` sent a request to the `store`. For changing the `state` of the application.  
  
  - After receiving the `request` for the `action` at the `store`. The `store` is called the `root reducer function` to perform an action and provide the next stage of the application. The `root reducers` perform the task using the divide-conquer. The `root reducer` divides the task in the smaller `reducer function` which all together performs the whole change state of the application.
  
  - Then these changes are sent to the middleware to test the `actions` whether these actions are valid for the store or not. And also perform the necessary changes in the action and then send them to the store.
  
  - When a `store` gets information about changing the `state` of the application. `Store` notifies the changes to the registered `listeners` that a state change has occurred. Then various parts of the application will be updated as required.


#### Q. What is the difference between React context and React Redux?

- You can use `Context` in your application directly.

- Whereas `Redux` is much more powerful and provides a large number of features that the Context API doesn't provide.
Also, React Redux uses context internally but it doesn't expose this fact in the public API.


#### Q. What is redux-saga?

- `redux-saga` is a library that aims to make side effects (asynchronous things like data fetching and impure things like accessing the browser cache) in React/Redux applications easier and better.
