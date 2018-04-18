# React

## Understand

Why it's **declarative** UI library.

JSX and how it is compiled to createElement functions.

Here's a typical React snippet:

    // button.js

    class Button extends React.Component {
      render() {
        return <div>Hello pesto!</div>;
      }
    }

What's going on here? Well, one initial impression could be that this file is mixing both Javascript and HTML into one file. Let's say you tried to throw that piece of code into the browser console with the `React` library in scope—it would immediately choke on that code. Fortunately for us, the above snippet never actually hits the browser, instead, it is first transpiled (via tools like Babel/Webpack) and eventually looks something similar to this:

    // transpiled-button.js

    React.createClass({
      render: function() {
        return React.createElement(
          'div',
          null,
          'Hello pesto!'
        )
      }
    });

The latter snippet is what React really looks like in its true form. Lucky for us, no one writes React like that (at least no one sane), so we use what is called JSX. JSX provides what we call syntactic sugar, a delicious coating over what is otherwise unintelligible and/or painful to read. It's also a really big reason why React is awesome—you can basically write your HTML as Javascript and vice-versa! As you'll see, JSX is a powerful means for writing clever code. But it is good to remember that at the end of the day, the code that actually ends up running looks a lot like `transpiled-button.js`.

Components and Props

state and setState

Let's say you have a component with buttons that changes the color of a div:

If you're checking out the code that generates this UI, there's a lot going on here. Let's break down the things to pay attention to here. First, there is a constructor that is declaring `this.state = { currentColor: 'red' }`. The property `state` is reserved namespace for React, and comes with a baked in API, such as `setState`, which you can see in the below method `changeColor`. The cool part about state is that you can reference it within your component, and expect its value to change if it's mutated in any other part of the component. In this example, we use it as an inline style (`backgroundColor`), that gets set on the `div`. As you can see, when you click either button, it'll trigger the `onClick` attribute, which will eventually call `setState` with the new color.

We highly recommend reading about state more in-depth [here](https://reactjs.org/docs/state-and-lifecycle.html), as you'll use it often. One important note about the setState method is that it is asynchronous, meaning that you can't depend on the value of this.state to be set correctly immediately following a setState invocation. By way of example:

    // bad
    console.log(this.state.currentColor); // logs 'blue'
    this.setState({ currentColor: 'red' });
    console.log(this.state.currentColor); // could log 'blue'

    // good
    console.log(this.state.currentColor); // logs 'blue'
    this.setState({ currentColor: 'red' }, () => {
      console.log(this.state.currentColor); // logs 'red'
    });

In the second snippet, we are using the optional callback argument in `setState` to have a dependable way of accessing the expected state.

Lifecycle Hooks

You may have noticed that we usually declare our React components like this:

    class Button extends React.Component { ... }

So we are declaring a class, that is an extension of `React.Component`. That means that this component comes baked with a bunch of methods ready to use. You've already seen a few, such as `render()` and `setState()`. (In case you were wondering, the `constructor()` method is a convention of Javascript classes, very similar to other object-oriented languages). A subset of these baked in methods are what we call lifecycle methods. Lifecycle methods are a great way for us devs to hook into different junctures in a components life, such as rendering (`render`), right after initial rendering (`componentDidMount`), before the component is taken away from the DOM (`componentWillUnmount`), etc. (Full list [HERE](https://reactjs.org/docs/react-component.html#unsafe_componentwillreceiveprops)). 

A common use case for one such lifecycle method, `componentDidMount`, is when you want to trigger a http request from your application as a component appears on the page. 

Event Handling

When you write your JSX `<div>`, per our JSX section above, you know now that you aren't really writing a vanilla HTML div. In reality, it comes packaged in a React context. So to that end, event handling in React (such as `onclick`, `onfocus`, etc.) looks a little different than if you were to attach those events directly to a true HTML element. For instance, the below is an example of a React div with an onClick event handler:

    class ClickableDiv extends React.Component {
      render() {
        return (
          <div onClick={() => console.log('I got clicked!')}>Click me!</div>
        );
      }
    }

Ok so maybe not that different. The big difference we're seeing here is that instead of an all lowercase onclick, we're seeing a camelcase onClick. Seems straightforward enough right? Also, suppose we were to have written that same event handler like this:

    <div onClick={console.log('I got clicked!')}>Click me!</div>

What would be the expected behavior? Well, since everything in curly brackets (`{ ... }`) is evaluated as Javascript, then we can expect that when this component initially renders, it will immediately log `'I got clicked'`, as opposed to waiting for you to click the div. 

Iteration and use of key prop

In case you're not sold on the powers of JSX, check out this snippet:

Here, we are returning an array of HTML tags, and it just works! You'll quickly find that being able to render an array of items in React is an indispensable tool. For instance, instead of an array of strings, what if you had to render an array of objects?

    // movies.js

    const movies = [ 
      { name: 'Awaara', year: 1951 },
      { name: 'Mother India', year: 1957 },
      { name: 'Awaara', year: 1951 },
      { name: 'Mother India', year: 1957 },
      { name: 'Pyaasa', year: 1957 },
      { name: 'Guide', year: 1965 },
      { name: 'Ankur', year: 1974 },
      { name: 'Sholay', year: 1975 },
      { name: 'Bombay', year: 1995 },
      { name: 'Deewaar', year: 1975 },
    ]

Easy! All you have to do is pull those properties out and presto! It works:

    // movies.js

    ...
    <ul>
      {movieNames.map(({ name, year}) => <li key={name}>{name} - {year}</li>)}
    </ul>

You may have noticed the `key` property being passed to the `<li />` elements. This property is critical for React to work properly, and it will log an error if you don't include it as a prop. Its function is to provide React a marker by which to differentiate the adjacent `<li />` elements when state/props are updated. Check out the 'Virtual DOM' section below for more info on this concept, but the basic idea is that React doesn't know for certain which `<li />` element is which, so you need to provide˜ a manual marker for it to render properly.

## Advance

- [Reconciliation](https://reactjs.org/docs/reconciliation.html)

- [Virtual DOM](https://reactjs.org/docs/faq-internals.html#what-is-the-virtual-dom)

## Resources

- [React Docs](https://reactjs.org/docs/hello-world.html)

- [React Bits](https://vasanthk.gitbooks.io/react-bits/)

- Styles in React
  - [CSS Evolution: From CSS, SASS, BEM, CSS Modules to Styled Components](https://medium.com/@perezpriego7/css-evolution-from-css-sass-bem-css-modules-to-styled-components-d4c1da3a659b)

  - [React JS Style Components](https://www.youtube.com/watch?v=gNeavlJ7lNY&app=desktop)
  
- [Awesome React](https://github.com/enaqx/awesome-react)
- [Flux Standard Actions](https://github.com/acdlite/flux-standard-action)
- [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
- [Composition vs Inheritance](https://reactjs.org/docs/composition-vs-inheritance.html)
- [Compound Components](https://www.youtube.com/watch?v=hEGg-3pIHlE&feature=youtu.be)
- [React Component Patterns by Michael Chan](https://www.youtube.com/watch?v=YaZg8wg39QQ)
- [create-react-app](https://github.com/facebook/create-react-app)
- [Top React and Redux Packages for Faster Development](https://codeburst.io/top-react-and-redux-packages-for-faster-development-5fa0ace42fe7)
- Setting up a react project without create-react-app [[Part 1](https://codeburst.io/yet-another-beginners-guide-to-setting-up-a-react-project-part-1-bdc8a29aea22) | [Part 2](https://codeburst.io/yet-another-beginners-guide-to-setting-up-a-react-project-part-2-5d3151814333)]
- [Common anti-patterns and gotchas in React](https://codeburst.io/how-to-not-react-common-anti-patterns-and-gotchas-in-react-40141fe0dcd)