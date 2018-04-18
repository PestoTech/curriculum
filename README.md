# **Curriculum**

# Introduction

These are the essential skills that every engineer attending the Pesto Bootcamp must be familiar with. We have built up this resource library by creating our own internal content and by curating our favorite blog posts, documentation sites and courses from around the web.

Here, you have access to resources which will help you understand the general programming concepts as well as the specifics of various technologies in depth.

# Getting Started

> Each section should be completed in order from top to bottom because some of the skills build on each other.

## Clean Code

It is really a very simple concept but one that sparked more debates and controversies than anything else in Computer Science. If you have ever thought about Tabs versus Spaces, snake_case versus CamelCase, verbNoun variable nomenclature or nounVerb, using is with booleans, or right level of abstraction then you know what it means. However, it is just the beginning. It's there in mathematics too. Mathematicians G.H Hardy and Betrand Russell use the term `elegance` and `rigour` for mathematical beauty. The term itself `Clean Code` is sufficiently descriptive and intuitively sensible, yet to put it into practice is as hard as composing a sonata, writing an opus, sculpting David and painting [The Last Supper](https://en.wikipedia.org/wiki/The_Last_Supper_(Leonardo_da_Vinci)). So if you are new to this concept, begin with the following links to get a gist of it. You'll get an idea about the same and form an opinion.

In short Clean Code is -

- Easy to understand.
- Easy to modify.
- Easy to test.
- Works correctly

Also, **if you always remember that code is written to read (by humans)** and not *just* to be executed, you'll mostly be on the right track.


- #### Articles
  - [What is Clean Code and why should you care?](http://cvuorinen.net/2014/04/what-is-clean-code-and-why-should-you-care/)

  - [Steps to better code](https://medium.com/@isaaclyman/steps-to-better-code-e6c3cce0c7f9)

  - [Clean code because it’s fun](https://medium.com/@adamzerner/clean-code-because-its-fun-71e45662a944)

  - [Keeping your code clean](https://codeburst.io/keeping-your-code-clean-d30bcffd1a10)

- #### Books
  - ***Structure and Interpretation of Computer Programs*** by Hal Abelson, Gerald Jay Sussman

  - ***Clean Code***, ***Agile Software Development*** and ***Clean Architecture*** by R C Martin.

  - ***Code Complete*** (2nd Edition) by Steve McConnell

  - ***Programming Pearls*** by Jon Bentley
  
  - ***Design Patterns*** by the Gang of Four (one of the best books for program architecture)

## Resources:

# Setting up environment ([details](https://github.com/PestoTech/curriculum/tree/master/Setting%20up%20environment#setting-up-environment))

- #### [Z Shell](https://github.com/PestoTech/curriculum/tree/master/Setting%20up%20environment#z-shell)
- #### [Editor](https://github.com/PestoTech/curriculum/tree/master/Setting%20up%20environment#editor)

  - [VSCode](https://github.com/PestoTech/curriculum/tree/master/Setting%20up%20environment#vscode)

  - [Basic Vim](https://github.com/PestoTech/curriculum/tree/master/Setting%20up%20environment#basic-vim-for-git-rebase-and-in-terminal-editing) (for Git Rebase and in-terminal editing)
- #### [Terminal and Commands](https://github.com/PestoTech/curriculum/tree/master/Setting%20up%20environment#terminal-and-commands)

- #### [Version Managers](https://github.com/PestoTech/curriculum/tree/master/Setting%20up%20environment#version-managers)

  - Node Version Manager

- #### [Package Managers](https://github.com/PestoTech/curriculum/tree/master/Setting%20up%20environment#package-managers)

  - [yarn](https://yarnpkg.com/lang/en/)

  - [npm](https://docs.npmjs.com/getting-started/what-is-npm)(along with [npx](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b))

  - Homebrew (macOS)
- #### [Environment Variables and uses](https://github.com/PestoTech/curriculum/tree/master/Setting%20up%20environment#environment-variables-and-uses)

- # Version Control
  - ### [Centralized and Distributed](https://www.atlassian.com/blog/software-teams/version-control-centralized-dvcs)

    - What are the advantages of Distributed over centralized.

    - Why distributed is preferred versus Centralized.

  - ### Git and GitHub ( Know the difference )

    - Various other git services providers

  - ### Git

    - #### Repositories (forking and cloning and the difference between them)

      - How to create

      - What are README files

      - How to read other people's repositories

    - #### gitignore files

      - Why it is required?

      - What are important things to put in it?

        - Logs

        - Compiled Binaries

        - Coverage Reports

        - Intermediate Files

    - #### Commits

      - What is a commit

      - Why commit often and in a logically coherent units

      - Difference between staging area, index area, and, working directory commit

      - Conventions to follow during a commit

      - Searching through a commit

    - #### Branching and Merging

      - Branch as an abstraction unit

      - Why branching is required?

      - How it handles features and allows multiple people to work on the same repo without collisions.

      - Checkout a branch

      - Conventions to follow for a branch name

      - Why `master`  exists

      - HEAD and branch references

    - #### [Reset](https://www.atlassian.com/git/tutorials/undoing-changes/git-reset)

      - What is a reset?

      - Difference between hard, soft, and mixed reset.

      - When to do reset?

    - #### [Stashing](https://medium.freecodecamp.org/useful-tricks-you-might-not-know-about-git-stash-e8a9490f0a1a)

      - Why stashing is required?

      - How to keep stashes of files

      - How to pop them back

    - #### Issues and Pull requests (Github)

      - What is an issue?

      - Atomic PRs

      - How to create an issue

      - How to assign it to a member?

      - How to create a Pull Request referencing that issue

      - How to review a PR

    - #### Git commands ( with common flags )
    
      - init

      - clone

      - add

      - commit

      - remote
    
      - pull ( vs fetch and its difference)
    
      - push
    
      - merge
    
      - branch
    
      - checkout
    
      - status
    
      - diff
    
      - log
    
    - #### Git Rebase

      - Why Rebase (vs merge)

      - Interactive rebase options

      - Rebase [ Udacity's [GitHub and Collaboration](https://in.udacity.com/course/github-collaboration--ud456) Course by **Richard Kalehoff** ]

      - [Git team workflows: Merge or Rebase](https://www.atlassian.com/git/articles/git-team-workflows-merge-or-rebase)

      - [Merging vs Rebasing](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)

      - [How to rebase and update a pull request](https://www.digitalocean.com/community/tutorials/how-to-rebase-and-update-a-pull-request)

      - [Rebase and merge pull requests](https://github.com/blog/2243-rebase-and-merge-pull-requests)

    - #### [Commit message style guides](https://chris.beams.io/posts/git-commit/)

      - [Udacity Commit Message Style Guide](https://udacity.github.io/git-styleguide/)

    - #### [Atomic commits](https://www.freshconsulting.com/atomic-commits/)

  - ### Additional Resources
    - #### [Git Cheat Sheet](https://github.com/github/training-kit/blob/master/downloads/github-git-cheat-sheet.pdf)

    - #### [Version Control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)

    - #### [Git Basics](https://medium.com/designing-atlassian/learn-to-love-git-part-one-the-basics-90429f456ace)

    - #### [Try Git](https://try.github.io/) tutorial

    - #### [gitignore](https://help.github.com/articles/ignoring-files/)

    - #### Understand branching and merge

      - [Using Branches](https://www.atlassian.com/git/tutorials/using-branches)

      - [Creating new branch and managing branches](https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches)

      - [Git branch](https://learngitbranching.js.org/) tutorial

    - #### [Github issues](https://guides.github.com/features/issues/) and [pull Requests](https://yangsu.github.io/pull-request-tutorial/)
    
    - #### [Git commands](https://medium.freecodecamp.org/git-cheat-sheet-and-best-practices-c6ce5321f52)

    - #### MOOC Courses
      
      - Udacity's Version Control with Git [ [Link](https://in.udacity.com/course/version-control-with-git--ud123) ]

      - Udacity's How to use Git and Github [ [Link](https://in.udacity.com/course/how-to-use-git-and-github--ud775) ]

      - Egghead's [Practical Git](https://egghead.io/courses/practical-git-for-everyday-professional-use)

    - [http://ohshitgit.com/](http://ohshitgit.com/)

  - #### Extra References

    - [Awesome Git](https://github.com/dictcp/awesome-git) - A list of curated resources about git and associated technologies.

    - [Pro Git](https://git-scm.com/book) - free Git book (CC BY-NC-SA 3.0) - A comprehensive reference on git and its internals.
    
- Javascript
  - ES5
    - Basic Language Features
      - [Expressions Versus Statements](http://2ality.com/2012/09/expressions-vs-statements.html)
      - [Control Flow Statements](http://www.culttt.com/2012/10/29/javascript-control-flow-structures/) and [Blocks](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/block)
      - Comments
        - How to write good comments
        - Why comment should not be written
        - Links: [[1](https://medium.freecodecamp.org/code-comments-the-good-the-bad-and-the-ugly-be9cc65fbf83), [2](https://dzone.com/articles/5-best-practices-commenting), [3](https://blog.codinghorror.com/code-tells-you-how-comments-tell-you-why/)]
      - [Strict Mode](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode)
      - [JavaScript’s Type System](http://2ality.com/2013/09/types.html)
        - Static Versus Dynamic
        - JS Types
        - Static Typing Versus Dynamic Typing
        - Static Type Checking Versus Dynamic Type Checking
        - Coercion
        - Resources:
          - [An explanation of JavaScript’s weird type system](https://medium.com/dailyjs/the-why-behind-the-wat-an-explanation-of-javascripts-weird-type-system-83b92879a8db)
      - Primitive Values Versus Objects
        - [JavaScript Primitive vs. Reference Values](http://www.javascripttutorial.net/javascript-primitive-vs-reference-values/)
        - [The Difference Between Boolean Objects and Boolean Primitives in JavaScript](http://adripofjavascript.com/blog/drips/the-difference-between-boolean-objects-and-boolean-primitives-in-javascript.html)
      - undefined and null
        - [What’s the difference between Null & Undefined?](https://codeburst.io/javascript-whats-the-difference-between-null-undefined-37793b5bfce6)
      - [Equality Operators: === Versus ==](https://codeburst.io/javascript-showdown-vs-7be792be15b5)
      - [Logical Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_Operators)
      - [Truthy vs Falsy values](http://adripofjavascript.com/blog/drips/truthy-and-falsy-values-in-javascript.html)
      - [Bitwise Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators)
        - [Using JavaScript’s Bitwise Operators in Real Life](https://codeburst.io/using-javascript-bitwise-operators-in-real-life-f551a731ff5)
      - String
        - Unicode
          - Code Points
          - Size in bytes of a single char
          - [Unicode and javascript](http://speakingjs.com/es5/ch24.html)
        - Constructing Strings
        - Manipulation
        - Concatenation
      - Statements
        - Loops
          - for
          - while
          - do while
          - for in
        - if else
        - Switch
        - debugger statement
      - Functions
        - Roles of functions
          - Functions
          - Methods
          - Constructor/object factories
          - [Factory Functions vs Constructor Functions vs Classes](https://medium.com/javascript-scene/javascript-factory-functions-vs-constructor-functions-vs-classes-2f22ceddf33e)
        - Params vs Arguments

          The terms *parameter* and *argument* are often used interchangeably, because the context usually makes it clear what the intended meaning is. The following is a rule of thumb for distinguishing them.

          - *Parameters* are used to define a function. They are also called formal parameters and formal arguments. In the following example, `param1` and `param2`are parameters:

                function foo(param1, param2) {...}

          - *Arguments* are used to invoke a function. They are also called actual parameters and actual arguments. In the following example, `3` and `7` are arguments:

                foo(3, 7);

        - Defining Functions

          All functions are objects, instances of `Function`:

              function id(x) { return x; }
              console.log(id instanceof Function); // true

          Therefore, functions get their methods from `Function.prototype`.

          - **Function Expressions**

            A function expression produces a value—a function object. For example:

                var add = function (x, y) { return x + y };
                console.log(add(2, 3)); // 5

            The preceding code assigned the result of a function expression to the variable `add`and called it via that variable. The value produced by a function expression can be assigned to a variable (as shown in the example), passed as an argument to another function, and more. Because normal function expressions don’t have a name, they are also called *anonymous function expressions*.

            **Named function expressions**

            You can give a function expression a name. *Named function expressions* allow a function expression to refer to itself, which is useful for self-recursion:

                var fac = function me(n) {
                	if (n > 0) {
                		return n * me(n-1);
                	} else {
                		return 1;
                	}
                };
                console.log(fac(3)); // 6

            ## **NOTE**

            The name of a named function expression is only accessible inside the function expression:

                var repeat = function me(n, str) {
                	return n > 0 ? str + me(n-1, str) : '';
                };
                console.log(repeat(3, 'Yeah')); // YeahYeahYeah
                console.log(me); // ReferenceError: me is not defined

          - **Function Declarations**

            The following is a function declaration:

                function add(x, y) {
                	return x + y;
                }

            The preceding looks like a function expression, but it is a statement. It is roughly equivalent to the following code:

                var add = function (x, y) {
                	return x + y;
                };

            In other words, a function declaration declares a new variable, creates a function object, and assigns it to the variable.

          - **The Function Constructor**

            The constructor `Function()` evaluates JavaScript code stored in strings. For example, the following code is equivalent to the previous example:

                var add = new Function('x', 'y', 'return x + y');

            However, this way of defining a function is slow and keeps code in strings (inaccessible to tools). Therefore, it is much better to use a function expression or a function declaration if possible.

        - [Hoisting](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20%26%20closures/ch4.md)
        - More Control over Function Calls: call(), apply(), and bind()
          - [JavaScript’s this: how it works, where it can trip you up](http://2ality.com/2014/05/this.html)
          - [Javascript: call(), apply() and bind()](https://medium.com/@omergoldberg/javascript-call-apply-and-bind-e5c27301f7bb)
        - [Arguments object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/arguments)
        - [this inside function](http://2ality.com/2014/05/this.html)
        - The Scope of a Variable
          - [Variable scope](http://javascriptissexy.com/javascript-variable-scope-and-hoisting-explained/)
          - [YDNJS: Scope from a lower lever perspective](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20%26%20closures/ch1.md)
            - [Lexical Scope](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20%26%20closures/ch2.md)
        - closures
          - [What’s a JavaScript closure](https://medium.freecodecamp.org/whats-a-javascript-closure-in-plain-english-please-6a1fc1d2ff1c)
            - [An interactive tutorial for closure](https://jscomplete.com/labs/what-are-closures-in-javascript)
          - Why it's required in JS
            - [In-depth explanation of closure in YDKJS](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20%26%20closures/ch5.md)
          - [What are first class functions](https://hackernoon.com/javascript-and-functional-programming-pt-2-first-class-functions-4437a1aec217)
      - global/window object
        - [console](https://developer.mozilla.org/en-US/docs/Web/API/Console)
          - log
          - formatted output
        - [setTimeout](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/setTimeout)
          - [A good question on setTimeout](https://medium.com/coderbyte/a-tricky-javascript-interview-question-asked-by-google-and-amazon-48d212890703)
        - [setInterval](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/setInterval)
        - [clearInterval](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/clearInterval)
      - [Objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects)
        - Property Accessors ([Dot and square notation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Property_accessors))
        - [this in objects](http://2ality.com/2014/05/this.html)
          - Losing this When Extracting a Method
          - Functions Inside Methods Shadow this
          - Other [gotchas when using this](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/).
        - [Inheritance](https://www.digitalocean.com/community/tutorials/understanding-prototypes-and-inheritance-in-javascript)
          - [Prototypal Chain](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)
          - Sharing Data Between Objects via a Prototype
          - Setting and Deleting Affects Only Own Properties
          - [Javascript inheritance by examples](http://2ality.com/2012/01/js-inheritance-by-example.html)
        - Object reflective methods
          - [.keys](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys)
          - Check out all the methods of Object [here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object).
        - Accessors ([Getters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/get) and [Setters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/set))
        - [Property Attributes and Property Descriptors](http://2ality.com/2012/10/javascript-properties.html)
        - [Protecting Objects](http://2ality.com/2013/08/protecting-objects.html)
          - Sealing
          - Extensions
          - Freezing
          - Protection Is Shallow
      - Exception Handling
        - What Is Exception Handling?
        - Exception Handling in JavaScript
          - throw
          - [try-catch-finally](Languages  Edit  Advanced try...catch)
        - Error Constructors
        - Stack Traces
        - All these are explained [`here`](http://speakingjs.com/es5/ch14.html)
      - Arrays
        - Forms of objects

          > Arrays are list-like objects whose prototype has methods to perform traversal and mutation operations. Neither the length of a JavaScript array nor the types of its elements are fixed. Since an array's length can change at any time, and data can be stored at non-contiguous locations in the array, JavaScript arrays are not guaranteed to be dense; this depends on how the programmer chooses to use them. In general, these are convenient characteristics; but if these features are not desirable for your particular use, you might consider using typed arrays.

          Arrays cannot use strings as element indexes (as in an associative array) but must use integers. Setting or accessing via non-integers using bracket notation (or dot notation) will not set or retrieve an element from the array list itself, but will set or access a variable associated with that array's object property collection. The array's object properties and list of array elements are separate, and the array's traversal and mutation operations cannot be applied to these named properties.

        - Array Methods
          - [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
          - [Reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)
          - [Filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
          - [forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
        - [mutating and non-mutating methods](https://lorenstewart.me/2017/01/22/javascript-array-methods-mutating-vs-non-mutating/)
      - [Regular Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)
        - Quantifiers
        - Capture Groups
        - Flags
        - [.test](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/test)
        - [.match](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match)
        - [.exec](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/exec)
        - [A simple tool to play with regex](http://regexr.com/)
        - [In depth javascript regex](http://speakingjs.com/es5/ch19.html)
      - [Date object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)
        - Epoch time
        - [Understanding Date and Time in JavaScript](https://www.digitalocean.com/community/tutorials/understanding-date-and-time-in-javascript)
      - [JSON](https://www.json.org/)
        - [Working with JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)
        - [parse](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/parse)
        - [stringify](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify)
        - [difference between objects and JSON](https://stackoverflow.com/questions/8294088/javascript-object-vs-json)
        - serialisability
    - Modules
      - [JavaScript Modules: A Beginner’s Guide](https://medium.freecodecamp.org/javascript-modules-a-beginner-s-guide-783f7d7a5fcc)
      - [In-depth](http://exploringjs.com/es6/ch_modules.html)
    - Shallow copy and Deep Copy **(Important)**
      - [Copying objects in javascript](https://scotch.io/bar-talk/copying-objects-in-javascript)
      - How to deep copy
      - Why it's required
    - [instanceof](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/instanceof), [typeof](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/typeof), [new](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new)
      - [More about 'new'](https://codeburst.io/javascript-for-beginners-the-new-operator-cee35beb669e)
    - Pure, total and partial functions
      - [What are pure functions and why use them?](https://medium.com/@jamesjefferyuk/javascript-what-are-pure-functions-4d4d5392d49c)
      - [Pure versus impure functions](https://toddmotto.com/pure-versus-impure-functions)
      - Partial Functions
      - Functional perspective
        - [Decoupling methods from their objects](https://hackernoon.com/functional-javascript-decoupling-methods-from-their-objects-aa3ca13d7ae8)
        - [Function Composition For Every Day Use.](https://hackernoon.com/javascript-functional-composition-for-every-day-use-22421ef65a10)
      - Why it's better than loops
        - [map vs forEach vs for](https://ryanpcmcquen.org/javascript/2015/10/25/map-vs-foreach-vs-for.html)
        - [Rethinking JavaScript: Death of the For Loop](https://hackernoon.com/rethinking-javascript-death-of-the-for-loop-c431564c84a8) (Also read comments from the author for more context and why loops are a better choice in some cases)
    - Built In Modules
      - Boolean
      - Date
      - Error
      - Function
      - JSON
      - Math
        - NaN
        - Infinity
      - Number
    - [Concurrency Model and Event Loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop)
  - ES6
    - [Let](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let) and [Const](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const)
      - Lexical Scope vs Function Scope
      - Why const?
      - Only references are const
      - Temporal Dead Zone
      - [Variables and scoping in ECMAScript 6](http://2ality.com/2015/02/es6-scoping.html)
    - [Template Literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)
    - [Arrow Functions Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
      - this is lexical instead of bind
      - [versus normal functions](http://exploringjs.com/es6/ch_arrow-functions.html#sec_arrow-func-vs-normal-func)
    - [for-of](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of)
    - [default parameters](https://css-tricks.com/using-default-parameters-es6/)
    - [Named Params](http://exploringjs.com/es6/ch_parameter-handling.html#sec_named-parameters)
    - [Rest Params](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters)
    - [Tagged Templates](https://medium.freecodecamp.org/es6-tagged-template-literals-48a70ef3ed4d)
    - [De-structuring Assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)
    - [Shorthand Properties](https://www.eventbrite.com/engineering/learning-es6-enhanced-object-literals/)
    - [ES6 Modules](http://exploringjs.com/es6/ch_modules.html)
      - CJS
      - AMD
    - [Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
      - [then](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/then)
      - [catch](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/catch)
      - [finally](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/finally)
      - [all](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/all)
    - [Classes in ES6](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
      - How it's same as new Function
      - [In-Depth](http://exploringjs.com/es6/ch_classes.html)
    - [Computed Object properties](https://www.eventbrite.com/engineering/learning-es6-enhanced-object-literals/)
    - [Object.assign](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign)
    - [Async/Await](http://exploringjs.com/es2016-es2017/ch_async-functions.html) (Promises)
      - How it's based on Promises
    - [Symbols](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol)
    - [Maps](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map) and [WeakMaps](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap)
    - [Sets](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set) and [WeakSets](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakSet)
    - [Iterator Protocol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Iteration_protocols#The_iterator_protocol)
    - [Proxy](https://codeburst.io/understanding-javascript-proxies-by-examining-on-change-library-f252eddf76c2)
    - [Generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator)
    - [Iterators and generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Iterators_and_Generators)
    - [function*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function*)
    - [yield](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield)
    - [yield*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield*)
  - Style Guides
    - [AirBnB](https://github.com/airbnb/javascript)
      - [Breathing air into AirBnB’s JavaScript Style Guide](https://medium.freecodecamp.org/adding-some-air-to-the-airbnb-style-guide-3df40e31c57a)
      - [5 JavaScript Style Guides — Including AirBnB, GitHub, & Google](https://codeburst.io/5-javascript-style-guides-including-airbnb-github-google-88cbc6b2b7aa)
    - [Google](https://google.github.io/styleguide/jsguide.html)
    - [Standard JS](https://standardjs.com/rules.html)
- Frontend
  - HTML5
    - [Doctype](https://developer.mozilla.org/en-US/docs/Glossary/Doctype)
      - [Quirks Mode and Standards Mode](https://developer.mozilla.org/en-US/docs/Web/HTML/Quirks_Mode_and_Standards_Mode)
    - [head](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML) and [body](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body)
    - [Block elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements) vs [Inline Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elements)
    - [span vs div](https://stackoverflow.com/questions/183532/what-is-the-difference-between-html-tags-div-and-span)
    - [forms](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Your_first_HTML_form)
      - [How to structure an HTML form?](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/How_to_structure_an_HTML_form)
      - [Form Data Validation](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Form_validation)
      - input
      - textarea
      - basic attributes
        - [action](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Sending_and_retrieving_form_data)
        - [method](https://developer.mozilla.org/en-US/docs/Learn/HTML/Forms/Sending_and_retrieving_form_data)
    - [HTML meta tags](https://www.w3schools.com/tags/tag_meta.asp), ([MDN Link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta))
  - CSS3
    - [Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/Box_model)
    - [Grid Systems](https://www.w3schools.com/css/css_rwd_grid.asp)
    - Responsiveness
      - [9 basic principles of responsive web design](http://blog.froont.com/9-basic-principles-of-responsive-web-design/)
    - [Flex-box Model](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
      - [Flexbox froggy: Interactively learn flexbox](http://flexboxfroggy.com/)
    - Frameworks
    - [Pre-processors](https://developer.mozilla.org/en-US/docs/Glossary/CSS_preprocessor)
      - [CSS Preprocessors — Effective Tools for Faster Styling of Web Pages and User Interfaces](https://medium.com/@cabot_solutions/css-preprocessors-effective-tools-for-faster-styling-of-web-pages-and-user-interfaces-6ed4737a9804)
      - [Sass/SCSS](https://gist.github.com/jareware/4738651)
        - [How to use Sass Mixins](https://scotch.io/tutorials/how-to-use-sass-mixins)
    - [Post Processors](https://www.hongkiat.com/blog/css-post-processors-tips-resources/)
      - [Autoprefix](https://autoprefixer.github.io/)[e]()[r](https://autoprefixer.github.io/)
    - [CSS Basics](https://www.youtube.com/watch?v=s7ONvIgOWdM&list=PLqGj3iMvMa4IOmy04kDxh_hqODMqoeeCy) Videos
    - [CSS Positioning](https://www.youtube.com/watch?v=kejG8G0dr5U&list=PLqGj3iMvMa4L731ispRfGAabXeRpM4RL6) Videos
  - [JSON](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON) as [Data Exchange format](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)
  - Javascript Elements for Frontend
    - window object
    - document object
    - DOM manipulation
    - [Node](https://developer.mozilla.org/en-US/docs/Web/API/Node)/HTMLElement/HTMLList
    - Ajax
      - XMLHTTPRequest
      - axios
      - fetch API with Promises
    - canvas API and SVG
    - Video and audio APIs (`<video>` and `<audio>`)
  - React

    # Understand

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

    # Advance

    - [Reconciliation](https://reactjs.org/docs/reconciliation.html)
    - [Virtual DOM](https://reactjs.org/docs/faq-internals.html#what-is-the-virtual-dom)

    # Resources

    - [React Docs](https://reactjs.org/docs/hello-world.html) [**Important**]
    - [React Bits](https://vasanthk.gitbooks.io/react-bits/) [**Important**]
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
  - Redux
    - [Official Docs](https://redux.js.org/)
    - [When to use redux?](https://medium.com/dailyjs/when-do-i-know-im-ready-for-redux-f34da253c85f)
      - [You M](https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367)[IGHT]() [Not Need Redux](https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367) (By the creator of Redux: Dan Abramov)
  - Router

    > React Router is a collection of navigational components that compose declaratively with your application.

    - [Official Docs](https://reacttraining.com/react-router/web/guides/philosophy)
    - [A Simple React Router v4 Tutorial](https://medium.com/@pshrmn/a-simple-react-router-v4-tutorial-7f23ff27adf)
  - Storage
    - [Cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
    - [IndexDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)
    - [WebStorage](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API)
    - [Cache API](https://developer.mozilla.org/en-US/docs/Web/API/Cache#Browser_compatibility)
  - Localisation/Internationalization
    - Read [this](https://www.w3.org/International/questions/qa-i18n) to get an overview of what they are and the difference between them.
  - [Accessibility](https://developers.google.com/web/fundamentals/accessibility/)
    - [w3 docs](https://www.w3.org/WAI/intro/accessibility.php)
    - [Course on Udacity](https://in.udacity.com/course/web-accessibility--ud891)
  - Security
    - [XSS](https://excess-xss.com/)
    - [CSRF](https://en.wikipedia.org/wiki/Cross-site_request_forgery)
    - [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)
    - [CSP directives](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy)
  - [Cross Browser Testing](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/Introduction)
    - [Handling common HTML and CSS problems](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/HTML_and_CSS)
    - [Handling common JavaScript problems](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/JavaScript)
    - Browser specific modes
    - Polyfills
    - Shims
    - [Difference between polyfills and shims](http://2ality.com/2011/12/shim-vs-polyfill.html)
- Tooling
  - [Build Tools](http://www.lihaoyi.com/post/WhatsinaBuildTool.html) and Bundlers
    - [NPM Scripts](https://docs.npmjs.com/misc/scripts)
      - [NPM](https://deliciousbrains.com/npm-build-script/) [scripts]() [as a build tool](https://deliciousbrains.com/npm-build-script/)
    - [Gulp](https://github.com/gulpjs/gulp/blob/v3.9.1/docs/API.md)
    - [JavaScript build tools and automation systems](https://hackernoon.com/javascript-build-tools-and-automation-systems-9589c5c91ebe)
    - [Choosing a JavaScript build tool: to config or not config](https://dev.to/netlify/choosing-a-javascript-build-tool-to-config-or-not-config-2ia8)
    - [Making]() [a sense out of build tools](https://medium.freecodecamp.org/making-sense-of-front-end-build-tools-3a1b3a87043b)
    - [Module Bundling](https://medium.freecodecamp.org/javascript-modules-part-2-module-bundling-5020383cf306)
    - [Webpack](https://webpack.js.org/concepts/)

      # Understand

      Webpack is a magical bundler that turns your beautiful code into a garbled mess of unintelligible gobbly-gook. In other words, it is a code bundler like any other (e.g. `gulp`, `browserify`), but it is top dog at the moment and an essential tool for any proficient front-end dev. We highly recommend pouring through their [docs online](https://webpack.js.org/concepts/) for general concepts and api reference, which have gotten markedly better since Webpack 1.x. 

      An important takeaway from your learnings in Webpack is that all that cool stuff you can do with Javascript, i.e. JSX, flexible module imports (*.png, *.css, *.json, etc.), `async`/`await`, that's all stuff that Webpack helps make possible! Let's look at how a typical Javascript loader might look:

          module: { 
          	rules: [ 
          		{  test: /\.js$/,  loader: 'babel-loader' }
          	] 
          }

      So what is this module object telling us? It is saying that for every `.js` file it encounters (note the RegEx in the `test` value), it is saying use the `babel-loader`.

      This syntax is exactly the same for css:

          module: { 
          	rules: [ 
          		{  test: /\.js$/,  loader: 'babel-loader' },
          		{  test: /\.css$/,  loader: 'style-loader' },
          	] 
          }

      ...just a different loader! In this case, `style-loader`. So if not obvious already, a loader's purpose is to take code as input and turn into other code. That's it.

      You'll probably never see such a simple setup as the one above in a production-grade webpack config, but remember that all those crazy configuration options are just turning your code into more-different code. 

      Let's quickly highlight some of the amazing benefits of Webpack:

      - It helps make code cross-browser compatible so that you can use cutting edge EcmaScript features! And will do things like autoprefix your css with `-webkit` and `-mz` so you don't have to bloat your css files!
      - It helps minify your code, meaning less time waiting for pages to load and thus more $$ for everyone!
      - [Hot Module Reload](https://webpack.js.org/concepts/hot-module-replacement/)!!! (Seriously, this was a game changer. So much less time waiting for new builds).

      Happy learnings!

      **Resources**

      - [Web Tooling and Automation](https://in.udacity.com/course/web-tooling-automation--ud892) [Udacity's Course]
      - [Webpack.org](https://webpack.js.org/concepts/)
      - [Modern JavaScript Explained For Dinosaurs](https://medium.com/the-node-js-collection/modern-javascript-explained-for-dinosaurs-f695e9747b70)
      - [How it feels to learn JavaScript in 2016](https://hackernoon.com/how-it-feels-to-learn-javascript-in-2016-d3a717dd577f)
      - [Survive JS Webpack](https://survivejs.com/webpack/) - [Book]
  - Live Reloads (Hot Reloading and HMR)
    - [BrowserSync](https://browsersync.io/docs) for Responsive Designs
  - Linting
    - [ESLint](https://eslint.org/)
    - [Does linting make you a better developer](https://medium.com/chingu/does-linting-make-you-a-better-developer-c9c0f382aaf0)
    - [Husky](https://github.com/typicode/husky)
    - [lint-staged](https://github.com/okonet/lint-staged)
  - [Continuous Integration](https://www.digitalocean.com/community/tutorials/an-introduction-to-continuous-integration-delivery-and-deployment)
    - [How to get Continuous Integration right](https://hackernoon.com/how-to-get-continuous-integration-right-77bda4bc0d1f)
    - [Travis](https://travis-ci.org/)
    - [Jenkins](https://jenkins.io/doc/)
  - [Transpiler](https://en.wikipedia.org/wiki/Source-to-source_compiler)
    - [JavaScript transpilers: what and why](https://scotch.io/tutorials/javascript-transpilers-what-they-are-why-we-need-them)
    - [Babel](https://babeljs.io)
  - Optimizations
    - gZipping
      - [How GZIP compression works](http://blog.servergrove.com/2014/04/14/gzip-compression-works/)
    - [Minification](https://wp-rocket.me/blog/minification-explained-in-plain-english/)
    - [Minification vs gZipping](https://css-tricks.com/the-difference-between-minification-and-gzipping/)
    - Chunking
- Network, Protocols, Browsers
  - Google Chrome
    - [React DevTools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en)
    - [Redux DevTools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd)
    - [ModHeader](https://chrome.google.com/webstore/detail/modheader/idgpnmonknjnojddfkpgkljpfnnfcklj?hl=en)
    - [CodeClimate](https://codeclimate.com/browser-extension)
    - [ScratchJS](https://github.com/richgilbank/Scratch-JS) - Chrome extension to write Babel transpiled scripts directly in Chrome DevTools
  - Chrome DevTools
    - [Overview](https://developers.google.com/web/tools/chrome-devtools/)
    - [Dev Tips](https://umaar.com/dev-tips/) - Large collection of tips as animated gifs
  - [HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview) and [HTTP2](https://developers.google.com/web/fundamentals/performance/http2/)
  - [Client Server Architecture](https://en.wikipedia.org/wiki/Client%E2%80%93server_model)
    - [Client-Server Communication](https://in.udacity.com/course/client-server-communication--ud897) - Course on Udacity
  - SSH
    - [What is SSH and how it works](https://www.hostinger.in/tutorials/ssh-tutorial-how-does-ssh-work#What-is-SSH)
  - HTTP Headers
    - Accept
    - Accept-Charset
    - Accept-Encoding
    - CORS Headers
    - Authorization
    - Content-Length
    - Content-Type
    - Referrer
  - HTTP Request Methods
    - GET
    - POST
    - DELETE
    - PUT
    - OPTIONS
    - HEAD
  - HTTP Response Status Codes
    - 2XX Series
    - 3XX Series
    - 4XX Series
    - 5XX Series
  - All the HTTP resources can be found [here](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)
  - [Postman](https://www.getpostman.com/docs/v6/)
- Algorithm/Data Structures
  - Data Structure
    - Big O Notation and complexity analysis
    - Stacks
    - Queues
    - Linked lists
    - Hash tables
    - Trees and BST
    - Graphs
  - Algorithms
    - Sorting
    - Search
    - Random Numbers
    - Primality Testing
  - Make a TicTacToe Game
- Backend
  - Node
    - V8 engine (and how it is important to Node)
      - [How JavaScript engines work](https://www.youtube.com/watch?v=p-iiEDtpy6I)
      - [Inside the V8 engine + 5 tips on how to write optimized code](https://blog.sessionstack.com/how-javascript-works-inside-the-v8-engine-5-tips-on-how-to-write-optimized-code-ac089e62b12e)
    - Deferred Execution (process.nextTick)
    - Event Loop
      - [Event Loop, Timers, and process.nextTick()](https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/)
      - [What the heck is the event loop?](https://www.youtube.com/watch?v=8aGhZQkoFbQ)
      - [In the loop](https://www.youtube.com/watch?v=cCOL7MC4Pl0) - Talk by Jake Archibald
    - [Overview of Blocking vs Non-Blocking](https://nodejs.org/en/docs/guides/blocking-vs-non-blocking/)
    - [Don't Block the Event Loop (or the Worker Pool)](https://nodejs.org/en/docs/guides/dont-block-the-event-loop/)
    - [Timers in Node.js](https://nodejs.org/en/docs/guides/timers-in-node/)
    - Request/Response cycle
    - http, fs, process modules
    - EventEmitter
      - [Understanding Node.js Event-Driven Architecture](https://medium.freecodecamp.org/understanding-node-js-event-driven-architecture-223292fcbc2d)
    - Streams
    - Buffers
    - Error Conventions
    - Node's Single threaded model.
    - Creating child processes.
    - Garbage Collection.

    **Resources**

    - [Official Docs](https://nodejs.org/docs/latest/api/)
    - [Awesome NodeJS](https://github.com/sindresorhus/awesome-nodejs)
  - Express
    - [MVC](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller) (Model, View, Controller)
      - [Model-View-Controller (MVC) Explained Through Ordering Drinks At The Bar](https://medium.freecodecamp.org/model-view-controller-mvc-explained-through-ordering-drinks-at-the-bar-efcba6255053)
    - [morgan](https://github.com/expressjs/morgan) - log each request
    - [cors](https://github.com/expressjs/cors) - enable CORS
    - [body-parser](https://github.com/expressjs/body-parser) - Node.js body parsing middleware
    - [Helmet.js](https://github.com/helmetjs/helmet) - help secure Express apps with various HTTP headers

    **Resources**

    - [Official Docs](https://expressjs.com/en/4x/api.html)
    - [Github Repo](https://github.com/expressjs/express)
  - Mongo
    - SQL vs MongoDB ( Know the difference )
    - Introduction to the Mongo Shell, JSON, BSON, and the MongoDB query language
    - ORM
    - CRUD
    - collections
    - documents
    - `mongod`
    - daemons
    - models
    - Mongo Shell, Query Operators, Update Operators
    - Deeper dive on the Node.js MongoClient driver; CRUD operations in the driver; Cursors
    - Schema Design
    - Aggregation Framework
      - $unwind
      - $group
      - $project
    - [Indexing](https://docs.mongodb.com/manual/indexes/?searchProperty=all&query=indexing) and [performance concepts](https://docs.mongodb.com/manual/administration/analyzing-mongodb-performance/index.html)
    - [Mongoose](http://mongoosejs.com/docs/guide.html)

    **Resources**

    - [MongoDB Docs](https://docs.mongodb.com/)
    - [MongoDB basics](https://university.mongodb.com/courses/M001/about)
    - [MongoDB for Node.js Developers](https://university.mongodb.com/courses/M101JS/about)
    - [Aggregation framework](https://university.mongodb.com/courses/M121/about)
  - Auth
    - [bcrypt-nodejs](https://www.npmjs.com/package/bcrypt-nodejs)
    - [jwt-simple](https://github.com/hokaccha/node-jwt-simple)
    - [passport](https://github.com/jaredhanson/passport)
    - [passport-jwt](https://github.com/themikenicholson/passport-jwt)
    - [passport-local](https://github.com/jaredhanson/passport-local)
    - salt
    - rainbow tables
    - never store plain-text passwords
    - JWT
    - token-based authentication
    - stateless authentication
    - JWT secret
  - APIs
    - Rest
    - GraphQL

      # Understand

      - The type system
      - Queries and mutations
      - Resolvers
      - Fields
      - Arguments
      - Aliases
      - Fragments
      - Operation Name
      - Variables
      - Directives
      - Mutations
      - Inline Fragments
      - [Apollo Ecosystem](https://www.apollographql.com/) [They have their own docs]
        - [Official Docs](https://www.apollographql.com/docs/)
        - apollo-client
        - apollo-server
        - graphql-tools

      # Resources

      - [Official Docs](http://graphql.org/) [Read the **Learn** Segment for most of **Understand** Section]
      - Articles
        - [So what’s this GraphQL thing I keep hearing about?](https://medium.freecodecamp.org/so-whats-this-graphql-thing-i-keep-hearing-about-baf4d36c20cf) [B]
        - [REST APIs are REST-in-Peace APIs. Long Live GraphQL.](https://medium.freecodecamp.org/rest-apis-are-rest-in-peace-apis-long-live-graphql-d412e559d8e4) [B]
        - [The Anatomy of a GraphQL Query](https://dev-blog.apollodata.com/the-anatomy-of-a-graphql-query-6dffa9e9e747) [B]
        - [GraphQL vs. REST](https://dev-blog.apollodata.com/graphql-vs-rest-5d425123e34b) [M]
        - [Full-stack React + GraphQL Tutorial](https://dev-blog.apollodata.com/full-stack-react-graphql-tutorial-582ac8d24e3b) [M, **Requires React**]
        - [The GraphQL stack: How everything fits together](https://dev-blog.apollodata.com/the-graphql-stack-how-everything-fits-together-35f8bf34f841)
        - [Tutorial: How to build a GraphQL server](https://dev-blog.apollodata.com/tutorial-building-a-graphql-server-cddaa023c035) [A]
        - [GraphQL schema stitching](https://dev-blog.apollodata.com/graphql-schema-stitching-8af23354ac37) [A]
        - [GraphQL Fragments are the Best Match for UI Components](https://blog.manifold.co/graphql-fragments-are-the-best-match-for-ui-components-72b8f61c20fe) [A]
        - [Five Common Problems in GraphQL Apps (And How to Fix Them)](https://medium.freecodecamp.org/five-common-problems-in-graphql-apps-and-how-to-fix-them-ac74d37a293c) [A]
      - Books
        - Learning GraphQL and Relay - Samer Buna

      ## Courses

      - Websites and Videos
        - [How to GraphQL](https://www.howtographql.com/)
      - **[Awesome GraphQL](https://github.com/chentsulin/awesome-graphql)**
- Testing
  - TDD

    > Something that is untested is broken.

    # Understand

    - Why testing is required?
    - Static (code reviews, inspection) vs. dynamic testing (running tests suites)
    - Black box and White Box testing
    - Testing Levels
      - Unit Testing
      - Integration Testing
      - System Testing
      - Alpha and Beta Testing
      - Functional and Non-Functional Testing
    - Mocks, Stubs, Fakes, Spies
    - Code Coverage Reports

    # Resources

    - Videos
      - [Test React applications using Enzyme & Jest](https://www.youtube.com/watch?v=8Ww2QBVIw0I)

    ## Testing Overview

    Software testing is one of the key parts of developing any application. Tests are where you write code to test your code. This helps prevent bugs and promotes cleaner code. It is also what allows us to use continuous deployment systems to deploy code confidently. With good test coverage, you no longer have to go through an manually click around to test your changes every time you push new code.

    - [Software Testing](https://en.wikipedia.org/wiki/Software_testing) [Read the portions mentioned in the Understand section]
    - [Open Lecture by James Bach on Software Testing](https://www.youtube.com/watch?v=ILkT_HV9DVU) [Video]
    - [Understanding how software testing works and what to test](https://stackoverflow.com/questions/3065485/understanding-how-software-testing-works-and-what-to-test)
    - [Test Doubles — Fakes, Mocks and Stubs.](https://blog.pragmatists.com/test-doubles-fakes-mocks-and-stubs-1a7491dfa3da)
    - [Mocks Aren't Stubs](https://martinfowler.com/articles/mocksArentStubs.html)

    ## Frontend Testing

    - [Unit Testing Front-End](https://medium.com/front-end-hacking/unit-testing-front-end-38b9bf1de079)
    - [The Front-End Test Pyramid: How to Rethink Your Testing](https://medium.freecodecamp.org/the-front-end-test-pyramid-rethink-your-testing-3b343c2bca51)
    - [Testing Your Frontend Code](https://hackernoon.com/testing-your-frontend-code-part-i-introduction-7e307eac4446) [Part 1 to 5]
    - [“Nobody cares about tests in front-end” Really?!](https://medium.com/rd-shipit/nobody-cares-about-tests-in-front-end-really-d1c8db7ba59d)
    - [A Skeptics Guide to Frontend Testing](https://codeburst.io/a-skeptics-guide-to-frontend-testing-part-1-5de4806ad300) [Part 1 to 3]

    ## Unit Tests

    Good unit tests should read like a set of instructions for the tested piece of code. A reader should be able to read through the tests and know immediately what the tested code is supposed to do, without having to look at the code itself.

    - [Unit testing Node.js with Tape](https://hackernoon.com/unit-testing-node-js-38cf2b7e1a41)
    - [My honest opinion about Unit Testing](https://hackernoon.com/my-honest-opinion-about-unit-testing-84eee5e893ad)
    - [5 Questions Every Unit Test Must Answer](https://medium.com/javascript-scene/what-every-unit-test-needs-f6cd34d9836d)

    ## Test Driven Development

    - [TDD the RITE Way](https://medium.com/javascript-scene/tdd-the-rite-way-53c9b46f45e3)
    - [Learn Test Driven Development](https://github.com/dwyl/learn-tdd) [Extensive Resource]

    ## Testing and TDD in JavaScript

    Every language has different ways to support the same principles with its own set of best-practices and common steps. Please focus on this part since most of our projects are made in JavaScript.

    Also, libraries such as React have their own standards and best practices in testing. We'll include that soon.

    - A Gentle Introduction To JavaScript TDD [[Part 1](https://jrsinclair.com/articles/2016/gentle-introduction-to-javascript-tdd-intro/), [Part 2](https://jrsinclair.com/articles/2016/gentle-introduction-to-javascript-tdd-ajax), [Part 3](https://jrsinclair.com/articles/2016/gentle-introduction-to-javascript-tdd-html-dom)]
    - [What is a Javascript Test ?](https://blog.kentcdodds.com/but-really-what-is-a-javascript-test-46fe5f3fad77)
    - [An Overview of JavaScript Testing in 2017](https://medium.com/powtoon-engineering/a-complete-guide-to-testing-javascript-in-2017-a217b4cd5a2a)
    - [JavaScript unit testing frameworks: Comparing Jasmine, Mocha, AVA, Tape and Jest](https://raygun.com/blog/javascript-unit-testing-frameworks/)
    - Udacity's [JavaScript Testing](https://in.udacity.com/course/javascript-testing--ud549) (UD549) [MOOC]

    ## Code Coverage

    - [The Importance of Code Coverage](https://blog.cloudboost.io/the-importance-of-code-coverage-9b4d513f39b4)

    # Pro Tips:

    ## Test your contract

    A good test should only test it's contract with the other pieces of software that will use that piece of code. The test should NOT be testing a piece of codes implementation.

    If tests are designed this way, you should be able to refactor any line of code in your implementation without having to refactor your tests.

    # Anti-Patterns

    ## Logic in the test assertion

    You should avoid adding logic whenever possible in the assertion part of your unit tests. This not only makes your tests harder to read but it also makes your test code more likely to have a bug, and therefore not actually test the original code properly.

    - [5 Common Misconceptions About TDD & Unit Tests](https://medium.com/javascript-scene/5-common-misconceptions-about-tdd-unit-tests-863d5beb3ce9)
  - Jest, Enzyme
    - [Expect](https://facebook.github.io/jest/docs/en/expect.html), [it](https://facebook.github.io/jest/docs/en/api.html#testname-fn-timeout), and [matchers](https://facebook.github.io/jest/docs/en/using-matchers.html)
    - Unit Testing
    - Snapshot Testing
      - [Snapshot testing React Components with Jest](https://hackernoon.com/snapshot-testing-react-components-with-jest-744a1e980366)
      - [Testing React Apps](https://facebook.github.io/jest/docs/en/tutorial-react.html)
      - [Testing React components with Jest and Enzyme](https://hackernoon.com/testing-react-components-with-jest-and-enzyme-41d592c174f)
      - [How to Snapshot Test Everything in Your Redux App With Jest](https://hackernoon.com/how-to-snapshot-test-everything-in-your-redux-app-with-jest-fde305ebedea)
      - [Video] [Snapshot testing - Anna Doubkova, React London 2017](https://www.youtube.com/watch?v=sCbGfi40IWk)
      - [Video] [Jest Snapshots and Beyond - React Conf 2017](https://www.youtube.com/watch?v=HAuXJVI_bUs)
    - E2E Testing
      - e2e or end-to-end or UI testing is a methodology used to test whether the flow of an application is performing as designed from start to finish. In simple words, it is testing of your application from the user endpoint where the whole system is a blackbox with only the UI exposed to the user.
      - [Why End-to-End Testing is Important for Your Team](https://medium.freecodecamp.org/why-end-to-end-testing-is-important-for-your-team-cb7eb0ec1504)
      - [End-to-end Tests that Don’t Suck with Puppeteer](https://ropig.com/blog/end-end-tests-dont-suck-puppeteer/)
      - [Tutorial: User Interface Testing with Jest and Puppeteer](https://www.valentinog.com/blog/ui-testing-jest-puppetteer/)
      - [A Guide to Automating & Scraping the Web with JavaScript](https://codeburst.io/a-guide-to-automating-scraping-the-web-with-javascript-chrome-puppeteer-node-js-b18efb9e9921)
- Deployment
  - Services
    - [Heroku](https://www.heroku.com/)
    - AWS Compute Engine
    - Serverless
  - Production
    - Secrets in Version Control Systems
    - Caching
    - CDNs
    - Horizontal / Vertical Scaling
    - Profilers
    - Load Balancers
    - Data Sharding/Duplication
    - Backups
- Ethical Concerns of Software Production and Engineering
- Tech Soft Skills
  - Take Responsibility/Ownership
  - Standups
  - WIP and when a PR is ready
  - Expectation of quality work
  - Over communicating
  - Spelling things right. Use spell-check editor in VSCode.
