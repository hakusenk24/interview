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
| 152 | [What is Flux?](#what-is-flux)                                                                                                                                                                                                   |
| 153 | [What is Redux?](#what-is-redux)                                                                                                                                                                                                 |
| 154 | [What are the core principles of Redux?](#what-are-the-core-principles-of-redux)                                                                                                                                                 |
| 155 | [What are the downsides of Redux compared to Flux?](#what-are-the-downsides-of-redux-compared-to-flux)                                                                                                                           |
| 156 | [What is the difference between mapStateToProps() and mapDispatchToProps()?](#what-is-the-difference-between-mapstatetoprops-and-mapdispatchtoprops)                                                                             |
| 157 | [Can I dispatch an action in reducer?](#can-i-dispatch-an-action-in-reducer)                                                                                                                                                     |
| 158 | [How to access Redux store outside a component?](#how-to-access-redux-store-outside-a-component)                                                                                                                                 |
| 159 | [What are the drawbacks of MVW pattern](#what-are-the-drawbacks-of-mvw-pattern)                                                                                                                                                  |
| 160 | [Are there any similarities between Redux and RxJS?](#are-there-any-similarities-between-redux-and-rxjs)                                                                                                                         |
| 161 | [How to dispatch an action on load?](#how-to-dispatch-an-action-on-load)                                                                                                                                                         |
| 162 | [How to use connect from React Redux?](#how-to-use-connect-from-react-redux)                                                                                                                                                     |
| 163 | [How to reset state in Redux?](#how-to-reset-state-in-redux)                                                                                                                                                                     |
| 164 | [Whats the purpose of at symbol in the redux connect decorator?](#whats-the-purpose-of-at-symbol-in-the-redux-connect-decorator)                                                                                                 |
| 165 | [What is the difference between React context and React Redux?](#what-is-the-difference-between-react-context-and-react-redux)                                                                                                   |
| 166 | [Why are Redux state functions called reducers?](#why-are-redux-state-functions-called-reducers)                                                                                                                                 |
| 167 | [How to make AJAX request in Redux?](#how-to-make-ajax-request-in-redux)                                                                                                                                                         |
| 168 | [Should I keep all component's state in Redux store?](#should-i-keep-all-components-state-in-redux-store)                                                                                                                        |
| 169 | [What is the proper way to access Redux store?](#what-is-the-proper-way-to-access-redux-store)                                                                                                                                   |
| 170 | [What is the difference between component and container in React Redux?](#what-is-the-difference-between-component-and-container-in-react-redux)                                                                                 |
| 171 | [What is the purpose of the constants in Redux? ](#what-is-the-purpose-of-the-constants-in-redux)                                                                                                                                |
| 172 | [What are the different ways to write mapDispatchToProps()?](#what-are-the-different-ways-to-write-mapdispatchtoprops)                                                                                                           |
| 173 | [What is the use of the ownProps parameter in mapStateToProps() and mapDispatchToProps()?](#what-is-the-use-of-the-ownprops-parameter-in-mapstatetoprops-and-mapdispatchtoprops)                                                 |
| 174 | [How to structure Redux top level directories?](#how-to-structure-redux-top-level-directories)                                                                                                                                   |
| 175 | [What is redux-saga?](#what-is-redux-saga)                                                                                                                                                                                       |
| 176 | [What is the mental model of redux-saga?](#what-is-the-mental-model-of-redux-saga)                                                                                                                                               |
| 177 | [What are the differences between call and put in redux-saga](#what-are-the-differences-between-call-and-put-in-redux-saga)                                                                                                      |
| 178 | [What is Redux Thunk?](#what-is-redux-thunk)                                                                                                                                                                                     |
| 179 | [What are the differences between redux-saga and redux-thunk](#what-are-the-differences-between-redux-saga-and-redux-thunk)                                                                                                      |
| 180 | [What is Redux DevTools?](#what-is-redux-devtools)                                                                                                                                                                               |
| 181 | [What are the features of Redux DevTools?](#what-are-the-features-of-redux-devtools)                                                                                                                                             |
| 182 | [What are Redux selectors and Why to use them?](#what-are-redux-selectors-and-why-to-use-them)                                                                                                                                   |
| 183 | [What is Redux Form?](#what-is-redux-form)                                                                                                                                                                                       |
| 184 | [What are the main features of Redux Form?](#what-are-the-main-features-of-redux-form)                                                                                                                                           |
| 185 | [How to add multiple middlewares to Redux?](#how-to-add-multiple-middlewares-to-redux)                                                                                                                                           |
| 186 | [How to set initial state in Redux?](#how-to-set-initial-state-in-redux)                                                                                                                                                         |
| 187 | [How Relay is different from Redux?](#how-relay-is-different-from-redux)                                                                                                                                                         |
| 188 | [What is an action in Redux?](#what-is-an-action-in-redux)                                                                                                                                                                       |

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

152. ### What is flux?

     _Flux_ is an _application design paradigm_ used as a replacement for the more traditional MVC pattern. It is not a framework or a library but a new kind of architecture that complements React and the concept of Unidirectional Data Flow. Facebook uses this pattern internally when working with React.

     The workflow between dispatcher, stores and views components with distinct inputs and outputs as follows:

**[⬆ Back to Top](#table-of-contents)**

153. ### What is Redux?

     _Redux_ is a predictable state container for JavaScript apps based on the _Flux design pattern_. Redux can be used together with React, or with any other view library. It is tiny (about 2kB) and has no dependencies.

**[⬆ Back to Top](#table-of-contents)**

154. ### What are the core principles of Redux?

     Redux follows three fundamental principles:

     1. **Single source of truth:** The state of your whole application is stored in an object tree within a single store. The single state tree makes it easier to keep track of changes over time and debug or inspect the application.
     2. **State is read-only:** The only way to change the state is to emit an action, an object describing what happened. This ensures that neither the views nor the network callbacks will ever write directly to the state.
     3. **Changes are made with pure functions:** To specify how the state tree is transformed by actions, you write reducers. Reducers are just pure functions that take the previous state and an action as parameters, and return the next state.

**[⬆ Back to Top](#table-of-contents)**

155. ### What are the downsides of Redux compared to Flux?

     Instead of saying downsides we can say that there are few compromises of using Redux over Flux. Those are as follows:

     1. **You will need to learn to avoid mutations:** Flux is un-opinionated about mutating data, but Redux doesn't like mutations and many packages complementary to Redux assume you never mutate the state. You can enforce this with dev-only packages like `redux-immutable-state-invariant`, Immutable.js, or instructing your team to write non-mutating code.
     2. **You're going to have to carefully pick your packages:** While Flux explicitly doesn't try to solve problems such as undo/redo, persistence, or forms, Redux has extension points such as middleware and store enhancers, and it has spawned a rich ecosystem.
     3. **There is no nice Flow integration yet:** Flux currently lets you do very impressive static type checks which Redux doesn't support yet.

**[⬆ Back to Top](#table-of-contents)**

156. ### What is the difference between `mapStateToProps()` and `mapDispatchToProps()`?

     `mapStateToProps()` is a utility which helps your component get updated state (which is updated by some other components):

     ```javascript
     const mapStateToProps = (state) => {
       return {
         todos: getVisibleTodos(state.todos, state.visibilityFilter),
       };
     };
     ```

     `mapDispatchToProps()` is a utility which will help your component to fire an action event (dispatching action which may cause change of application state):

     ```javascript
     const mapDispatchToProps = (dispatch) => {
       return {
         onTodoClick: (id) => {
           dispatch(toggleTodo(id));
         },
       };
     };
     ```

     It is recommended to always use the “object shorthand” form for the `mapDispatchToProps`.

     Redux wraps it in another function that looks like (…args) => dispatch(onTodoClick(…args)), and pass that wrapper function as a prop to your component.

     ```javascript
     const mapDispatchToProps = {
       onTodoClick,
     };
     ```

**[⬆ Back to Top](#table-of-contents)**

157. ### Can I dispatch an action in reducer?

     Dispatching an action within a reducer is an **anti-pattern**. Your reducer should be _without side effects_, simply digesting the action payload and returning a new state object. Adding listeners and dispatching actions within the reducer can lead to chained actions and other side effects.

**[⬆ Back to Top](#table-of-contents)**

158. ### How to access Redux store outside a component?

     You just need to export the store from the module where it created with `createStore()`. Also, it shouldn't pollute the global window object.

     ```javascript
     store = createStore(myReducer);

     export default store;
     ```

**[⬆ Back to Top](#table-of-contents)**

159. ### What are the drawbacks of MVW pattern?

     1. DOM manipulation is very expensive which causes applications to behave slow and inefficient.
     2. Due to circular dependencies, a complicated model was created around models and views.
     3. Lot of data changes happens for collaborative applications(like Google Docs).
     4. No way to do undo (travel back in time) easily without adding so much extra code.

**[⬆ Back to Top](#table-of-contents)**

160. ### Are there any similarities between Redux and RxJS?

     These libraries are very different for very different purposes, but there are some vague similarities.

     Redux is a tool for managing state throughout the application. It is usually used as an architecture for UIs. Think of it as an alternative to (half of) Angular. RxJS is a reactive programming library. It is usually used as a tool to accomplish asynchronous tasks in JavaScript. Think of it as an alternative to Promises. Redux uses the Reactive paradigm because the Store is reactive. The Store observes actions from a distance, and changes itself. RxJS also uses the Reactive paradigm, but instead of being an architecture, it gives you basic building blocks, Observables, to accomplish this pattern.

**[⬆ Back to Top](#table-of-contents)**

161. ### How to dispatch an action on load?

     You can dispatch an action in `componentDidMount()` method and in `render()` method you can verify the data.

     ```javascript
     class App extends Component {
       componentDidMount() {
         this.props.fetchData();
       }

       render() {
         return this.props.isLoaded ? (
           <div>{"Loaded"}</div>
         ) : (
           <div>{"Not Loaded"}</div>
         );
       }
     }

     const mapStateToProps = (state) => ({
       isLoaded: state.isLoaded,
     });

     const mapDispatchToProps = { fetchData };

     export default connect(mapStateToProps, mapDispatchToProps)(App);
     ```

**[⬆ Back to Top](#table-of-contents)**

162. ### How to use `connect()` from React Redux?

     You need to follow two steps to use your store in your container:

     1. **Use `mapStateToProps()`:** It maps the state variables from your store to the props that you specify.
     2. **Connect the above props to your container:** The object returned by the `mapStateToProps` function is connected to the container. You can import `connect()` from `react-redux`.

        ```jsx harmony
        import React from "react";
        import { connect } from "react-redux";

        class App extends React.Component {
          render() {
            return <div>{this.props.containerData}</div>;
          }
        }

        function mapStateToProps(state) {
          return { containerData: state.data };
        }

        export default connect(mapStateToProps)(App);
        ```

**[⬆ Back to Top](#table-of-contents)**

163. ### How to reset state in Redux?

     You need to write a _root reducer_ in your application which delegate handling the action to the reducer generated by `combineReducers()`.

     For example, let us take `rootReducer()` to return the initial state after `USER_LOGOUT` action. As we know, reducers are supposed to return the initial state when they are called with `undefined` as the first argument, no matter the action.

     ```javascript
     const appReducer = combineReducers({
       /* your app's top-level reducers */
     });

     const rootReducer = (state, action) => {
       if (action.type === "USER_LOGOUT") {
         state = undefined;
       }

       return appReducer(state, action);
     };
     ```

     In case of using `redux-persist`, you may also need to clean your storage. `redux-persist` keeps a copy of your state in a storage engine. First, you need to import the appropriate storage engine and then, to parse the state before setting it to undefined and clean each storage state key.

     ```javascript
     const appReducer = combineReducers({
       /* your app's top-level reducers */
     });

     const rootReducer = (state, action) => {
       if (action.type === "USER_LOGOUT") {
         Object.keys(state).forEach((key) => {
           storage.removeItem(`persist:${key}`);
         });

         state = undefined;
       }

       return appReducer(state, action);
     };
     ```

**[⬆ Back to Top](#table-of-contents)**

164. ### Whats the purpose of `at` symbol in the Redux connect decorator?

     The **@** symbol is in fact a JavaScript expression used to signify decorators. _Decorators_ make it possible to annotate and modify classes and properties at design time.

     Let's take an example setting up Redux without and with a decorator.

     - **Without decorator:**

       ```javascript
       import React from "react";
       import * as actionCreators from "./actionCreators";
       import { bindActionCreators } from "redux";
       import { connect } from "react-redux";

       function mapStateToProps(state) {
         return { todos: state.todos };
       }

       function mapDispatchToProps(dispatch) {
         return { actions: bindActionCreators(actionCreators, dispatch) };
       }

       class MyApp extends React.Component {
         // ...define your main app here
       }

       export default connect(mapStateToProps, mapDispatchToProps)(MyApp);
       ```

     - **With decorator:**

       ```javascript
       import React from "react";
       import * as actionCreators from "./actionCreators";
       import { bindActionCreators } from "redux";
       import { connect } from "react-redux";

       function mapStateToProps(state) {
         return { todos: state.todos };
       }

       function mapDispatchToProps(dispatch) {
         return { actions: bindActionCreators(actionCreators, dispatch) };
       }

       @connect(mapStateToProps, mapDispatchToProps)
       export default class MyApp extends React.Component {
         // ...define your main app here
       }
       ```

     The above examples are almost similar except the usage of decorator. The decorator syntax isn't built into any JavaScript runtimes yet, and is still experimental and subject to change. You can use babel for the decorators support.

**[⬆ Back to Top](#table-of-contents)**

165. ### What is the difference between React context and React Redux?

     You can use **Context** in your application directly and is going to be great for passing down data to deeply nested components which what it was designed for.

     Whereas **Redux** is much more powerful and provides a large number of features that the Context API doesn't provide. Also, React Redux uses context internally but it doesn't expose this fact in the public API.

**[⬆ Back to Top](#table-of-contents)**

166. ### Why are Redux state functions called reducers?

     Reducers always return the accumulation of the state (based on all previous and current actions). Therefore, they act as a reducer of state. Each time a Redux reducer is called, the state and action are passed as parameters. This state is then reduced (or accumulated) based on the action, and then the next state is returned. You could _reduce_ a collection of actions and an initial state (of the store) on which to perform these actions to get the resulting final state.

**[⬆ Back to Top](#table-of-contents)**

167. ### How to make AJAX request in Redux?

     You can use `redux-thunk` middleware which allows you to define async actions.

     Let's take an example of fetching specific account as an AJAX call using _fetch API_:

     ```javascript
     export function fetchAccount(id) {
       return (dispatch) => {
         dispatch(setLoadingAccountState()); // Show a loading spinner
         fetch(`/account/${id}`, (response) => {
           dispatch(doneFetchingAccount()); // Hide loading spinner
           if (response.status === 200) {
             dispatch(setAccount(response.json)); // Use a normal function to set the received state
           } else {
             dispatch(someError);
           }
         });
       };
     }

     function setAccount(data) {
       return { type: "SET_Account", data: data };
     }
     ```

**[⬆ Back to Top](#table-of-contents)**

168. ### Should I keep all component's state in Redux store?

     Keep your data in the Redux store, and the UI related state internally in the component.

**[⬆ Back to Top](#table-of-contents)**

169. ### What is the proper way to access Redux store?

     The best way to access your store in a component is to use the `connect()` function, that creates a new component that wraps around your existing one. This pattern is called _Higher-Order Components_, and is generally the preferred way of extending a component's functionality in React. This allows you to map state and action creators to your component, and have them passed in automatically as your store updates.

     Let's take an example of `<FilterLink>` component using connect:

     ```javascript
     import { connect } from "react-redux";
     import { setVisibilityFilter } from "../actions";
     import Link from "../components/Link";

     const mapStateToProps = (state, ownProps) => ({
       active: ownProps.filter === state.visibilityFilter,
     });

     const mapDispatchToProps = (dispatch, ownProps) => ({
       onClick: () => dispatch(setVisibilityFilter(ownProps.filter)),
     });

     const FilterLink = connect(mapStateToProps, mapDispatchToProps)(Link);

     export default FilterLink;
     ```

     Due to it having quite a few performance optimizations and generally being less likely to cause bugs, the Redux developers almost always recommend using `connect()` over accessing the store directly (using context API).

     ```javascript
     class MyComponent {
       someMethod() {
         doSomethingWith(this.context.store);
       }
     }
     ```

**[⬆ Back to Top](#table-of-contents)**

170. ### What is the difference between component and container in React Redux?

     **Component** is a class or function component that describes the presentational part of your application.

     **Container** is an informal term for a component that is connected to a Redux store. Containers _subscribe_ to Redux state updates and _dispatch_ actions, and they usually don't render DOM elements; they delegate rendering to presentational child components.

**[⬆ Back to Top](#table-of-contents)**

171. ### What is the purpose of the constants in Redux?

     Constants allows you to easily find all usages of that specific functionality across the project when you use an IDE. It also prevents you from introducing silly bugs caused by typos – in which case, you will get a `ReferenceError` immediately.

     Normally we will save them in a single file (`constants.js` or `actionTypes.js`).

     ```javascript
     export const ADD_TODO = "ADD_TODO";
     export const DELETE_TODO = "DELETE_TODO";
     export const EDIT_TODO = "EDIT_TODO";
     export const COMPLETE_TODO = "COMPLETE_TODO";
     export const COMPLETE_ALL = "COMPLETE_ALL";
     export const CLEAR_COMPLETED = "CLEAR_COMPLETED";
     ```

     In Redux, you use them in two places:

     1. **During action creation:**

        Let's take `actions.js`:

        ```javascript
        import { ADD_TODO } from "./actionTypes";

        export function addTodo(text) {
          return { type: ADD_TODO, text };
        }
        ```

     2. **In reducers:**

        Let's create `reducer.js`:

        ```javascript
        import { ADD_TODO } from "./actionTypes";

        export default (state = [], action) => {
          switch (action.type) {
            case ADD_TODO:
              return [
                ...state,
                {
                  text: action.text,
                  completed: false,
                },
              ];
            default:
              return state;
          }
        };
        ```

**[⬆ Back to Top](#table-of-contents)**

172. ### What are the different ways to write `mapDispatchToProps()`?

     There are a few ways of binding _action creators_ to `dispatch()` in `mapDispatchToProps()`.

     Below are the possible options:

     ```javascript
     const mapDispatchToProps = (dispatch) => ({
       action: () => dispatch(action()),
     });
     ```

     ```javascript
     const mapDispatchToProps = (dispatch) => ({
       action: bindActionCreators(action, dispatch),
     });
     ```

     ```javascript
     const mapDispatchToProps = { action };
     ```

     The third option is just a shorthand for the first one.

**[⬆ Back to Top](#table-of-contents)**

173. ### What is the use of the `ownProps` parameter in `mapStateToProps()` and `mapDispatchToProps()`?

     If the `ownProps` parameter is specified, React Redux will pass the props that were passed to the component into your _connect_ functions. So, if you use a connected component:

     ```jsx harmony
     import ConnectedComponent from "./containers/ConnectedComponent";

     <ConnectedComponent user={"john"} />;
     ```

     The `ownProps` inside your `mapStateToProps()` and `mapDispatchToProps()` functions will be an object:

     ```javascript
     {
       user: "john";
     }
     ```

     You can use this object to decide what to return from those functions.

**[⬆ Back to Top](#table-of-contents)**

174. ### How to structure Redux top level directories?

     Most of the applications has several top-level directories as below:

     1. **Components**: Used for _dumb_ components unaware of Redux.
     2. **Containers**: Used for _smart_ components connected to Redux.
     3. **Actions**: Used for all action creators, where file names correspond to part of the app.
     4. **Reducers**: Used for all reducers, where files name correspond to state key.
     5. **Store**: Used for store initialization.

     This structure works well for small and medium size apps.

**[⬆ Back to Top](#table-of-contents)**

175. ### What is redux-saga?

     `redux-saga` is a library that aims to make side effects (asynchronous things like data fetching and impure things like accessing the browser cache) in React/Redux applications easier and better.

     It is available in NPM:

     ```console
     $ npm install --save redux-saga
     ```

**[⬆ Back to Top](#table-of-contents)**

176. ### What is the mental model of redux-saga?

     _Saga_ is like a separate thread in your application, that's solely responsible for side effects. `redux-saga` is a redux _middleware_, which means this thread can be started, paused and cancelled from the main application with normal Redux actions, it has access to the full Redux application state and it can dispatch Redux actions as well.

**[⬆ Back to Top](#table-of-contents)**

177. ### What are the differences between `call()` and `put()` in redux-saga?

     Both `call()` and `put()` are effect creator functions. `call()` function is used to create effect description, which instructs middleware to call the promise. `put()` function creates an effect, which instructs middleware to dispatch an action to the store.

     Let's take example of how these effects work for fetching particular user data.

     ```javascript
     function* fetchUserSaga(action) {
       // `call` function accepts rest arguments, which will be passed to `api.fetchUser` function.
       // Instructing middleware to call promise, it resolved value will be assigned to `userData` variable
       const userData = yield call(api.fetchUser, action.userId);

       // Instructing middleware to dispatch corresponding action.
       yield put({
         type: "FETCH_USER_SUCCESS",
         userData,
       });
     }
     ```

**[⬆ Back to Top](#table-of-contents)**

178. ### What is Redux Thunk?

     _Redux Thunk_ middleware allows you to write action creators that return a function instead of an action. The thunk can be used to delay the dispatch of an action, or to dispatch only if a certain condition is met. The inner function receives the store methods `dispatch()` and `getState()` as parameters.

**[⬆ Back to Top](#table-of-contents)**

179. ### What are the differences between `redux-saga` and `redux-thunk`?

     Both _Redux Thunk_ and _Redux Saga_ take care of dealing with side effects. In most of the scenarios, Thunk uses _Promises_ to deal with them, whereas Saga uses _Generators_. Thunk is simple to use and Promises are familiar to many developers, Sagas/Generators are more powerful but you will need to learn them. But both middleware can coexist, so you can start with Thunks and introduce Sagas when/if you need them.

**[⬆ Back to Top](#table-of-contents)**

180. ### What is Redux DevTools?

     _Redux DevTools_ is a live-editing time travel environment for Redux with hot reloading, action replay, and customizable UI. If you don't want to bother with installing Redux DevTools and integrating it into your project, consider using Redux DevTools Extension for Chrome and Firefox.

**[⬆ Back to Top](#table-of-contents)**

181. ### What are the features of Redux DevTools?

     Some of the main features of Redux DevTools are below,

     1. Lets you inspect every state and action payload.
     2. Lets you go back in time by _cancelling_ actions.
     3. If you change the reducer code, each _staged_ action will be re-evaluated.
     4. If the reducers throw, you will see during which action this happened, and what the error was.
     5. With `persistState()` store enhancer, you can persist debug sessions across page reloads.

**[⬆ Back to Top](#table-of-contents)**

182. ### What are Redux selectors and why to use them?

     _Selectors_ are functions that take Redux state as an argument and return some data to pass to the component.

     For example, to get user details from the state:

     ```javascript
     const getUserData = (state) => state.user.data;
     ```

     These selectors have two main benefits,

     1. The selector can compute derived data, allowing Redux to store the minimal possible state
     2. The selector is not recomputed unless one of its arguments changes

**[⬆ Back to Top](#table-of-contents)**

183. ### What is Redux Form?

     _Redux Form_ works with React and Redux to enable a form in React to use Redux to store all of its state. Redux Form can be used with raw HTML5 inputs, but it also works very well with common UI frameworks like Material UI, React Widgets and React Bootstrap.

**[⬆ Back to Top](#table-of-contents)**

184. ### What are the main features of Redux Form?

     Some of the main features of Redux Form are:

     1. Field values persistence via Redux store.
     2. Validation (sync/async) and submission.
     3. Formatting, parsing and normalization of field values.

**[⬆ Back to Top](#table-of-contents)**

185. ### How to add multiple middlewares to Redux?

     You can use `applyMiddleware()`.

     For example, you can add `redux-thunk` and `logger` passing them as arguments to `applyMiddleware()`:

     ```javascript
     import { createStore, applyMiddleware } from "redux";
     const createStoreWithMiddleware = applyMiddleware(
       ReduxThunk,
       logger
     )(createStore);
     ```

**[⬆ Back to Top](#table-of-contents)**

186. ### How to set initial state in Redux?

     You need to pass initial state as second argument to createStore:

     ```javascript
     const rootReducer = combineReducers({
       todos: todos,
       visibilityFilter: visibilityFilter,
     });

     const initialState = {
       todos: [{ id: 123, name: "example", completed: false }],
     };

     const store = createStore(rootReducer, initialState);
     ```

**[⬆ Back to Top](#table-of-contents)**

187. ### How Relay is different from Redux?

     Relay is similar to Redux in that they both use a single store. The main difference is that relay only manages state originated from the server, and all access to the state is used via _GraphQL_ queries (for reading data) and mutations (for changing data). Relay caches the data for you and optimizes data fetching for you, by fetching only changed data and nothing more.
