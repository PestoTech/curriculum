- # Functions in JavaScript (ES5)

- ## Roles of functions

  - Functions

  - Methods

  - Constructor/object factories

  - [Factory Functions vs Constructor Functions vs Classes](https://medium.com/javascript-scene/javascript-factory-functions-vs-constructor-functions-vs-classes-2f22ceddf33e)

- ## Params vs Arguments

  The terms *parameter* and *argument* are often used interchangeably, because the context usually makes it clear what the intended meaning is. The following is a rule of thumb for distinguishing them.

  - *Parameters* are used to define a function. They are also called formal parameters and formal arguments. In the following example, `param1` and `param2` are parameters:

        function foo(param1, param2) {...}

  - *Arguments* are used to invoke a function. They are also called actual parameters and actual arguments. In the following example, `3` and `7` are arguments:

        foo(3, 7);

- ## Defining Functions

  All functions are objects, instances of `Function`:

      function id(x) { return x; }
      console.log(id instanceof Function); // true

  Therefore, functions get their methods from `Function.prototype`.

  - ### Function Expressions

    A function expression produces a value—a function object. For example:

        var add = function (x, y) { return x + y };
        console.log(add(2, 3)); // 5

    The preceding code assigned the result of a function expression to the variable `add` and called it via that variable. The value produced by a function expression can be assigned to a variable (as shown in the example), passed as an argument to another function, and more. Because normal function expressions don’t have a name, they are also called *anonymous function expressions*.

    #### Named function expressions

    You can give a function expression a name. *Named function expressions* allow a function expression to refer to itself, which is useful for self-recursion:

        var fac = function me(n) {
          if (n > 0) {
            return n * me(n-1);
          } else {
            return 1;
          }
        };
        console.log(fac(3)); // 6

    #### NOTE

    The name of a named function expression is only accessible inside the function expression:

        var repeat = function me(n, str) {
          return n > 0 ? str + me(n-1, str) : '';
        };
        console.log(repeat(3, 'Yeah')); // YeahYeahYeah
        console.log(me); // ReferenceError: me is not defined

  - ### Function Declarations

    The following is a function declaration:

        function add(x, y) {
          return x + y;
        }

    The preceding looks like a function expression, but it is a statement. It is roughly equivalent to the following code:

        var add = function (x, y) {
          return x + y;
        };

    In other words, a function declaration declares a new variable, creates a function object, and assigns it to the variable.

  - ### The Function Constructor

    The constructor `Function()` evaluates JavaScript code stored in strings. For example, the following code is equivalent to the previous example:

        var add = new Function('x', 'y', 'return x + y');

    However, this way of defining a function is slow and keeps code in strings (inaccessible to tools). Therefore, it is much better to use a function expression or a function declaration if possible.

- ## [Hoisting](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20%26%20closures/ch4.md)

- ## More Control over Function Calls: call(), apply(), and bind()
  - [JavaScript’s this: how it works, where it can trip you up](http://2ality.com/2014/05/this.html)

  - [Javascript: call(), apply() and bind()](https://medium.com/@omergoldberg/javascript-call-apply-and-bind-e5c27301f7bb)

- ## [Arguments object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/arguments)

- ## [`this` inside function](http://2ality.com/2014/05/this.html)

- ## The Scope of a Variable
  - [Variable scope](http://javascriptissexy.com/javascript-variable-scope-and-hoisting-explained/)

  - [YDNJS: Scope from a lower lever perspective](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20%26%20closures/ch1.md)

    - [Lexical Scope](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20%26%20closures/ch2.md)

- ## Closures

  - [What’s a JavaScript closure](https://medium.freecodecamp.org/whats-a-javascript-closure-in-plain-english-please-6a1fc1d2ff1c)

    - [An interactive tutorial for closure](https://jscomplete.com/labs/what-are-closures-in-javascript)

  - Why it's required in JS
    - [In-depth explanation of closure in YDKJS](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20%26%20closures/ch5.md)

  - [What are first class functions](https://hackernoon.com/javascript-and-functional-programming-pt-2-first-class-functions-4437a1aec217)