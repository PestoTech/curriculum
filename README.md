# *Curriculum*

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

  - ### Git Resources
    - #### [Git Cheat Sheet](https://github.com/github/training-kit/blob/master/downloads/github-git-cheat-sheet.pdf)

    - #### [Getting Started With Version Control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)

    - #### Basics - [Learn To Love Git](https://medium.com/designing-atlassian/learn-to-love-git-part-one-the-basics-90429f456ace)

    - #### [Try Git](https://try.github.io/) tutorial

    - #### [gitignore files](https://help.github.com/articles/ignoring-files/)

    - #### Understand branching and merge

      - [Using Branches](https://www.atlassian.com/git/tutorials/using-branches)

      - [Creating new branch and managing branches](https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches)

      - [Git branch](https://learngitbranching.js.org/) tutorial

    - #### [Github issues](https://guides.github.com/features/issues/) and [pull Requests](https://yangsu.github.io/pull-request-tutorial/)
    
    - #### [Git commands](https://medium.freecodecamp.org/git-cheat-sheet-and-best-practices-c6ce5321f52)

    - #### MOOC Courses
      
      - Udacity's Version Control with Git [ [Link](https://in.udacity.com/course/version-control-with-git--ud123) ]

      - Udacity's How to use Git and Github [ [Link](https://in.udacity.com/course/how-to-use-git-and-github--ud775) ]

    - [http://ohshitgit.com/](http://ohshitgit.com/)

  - #### Extra References

    - [Awesome Git](https://github.com/dictcp/awesome-git) - A list of curated resources about git and associated technologies.

    - [Pro Git](https://git-scm.com/book) - free Git book (CC BY-NC-SA 3.0) - A comprehensive reference on git and its internals.

- # Javascript
  - ## ES5
    - ### Basic Language Features
      - [Expressions Versus Statements](http://2ality.com/2012/09/expressions-vs-statements.html)

      - [Control Flow Statements](http://www.culttt.com/2012/10/29/javascript-control-flow-structures/) and [Blocks](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/block)

      - #### Comments
        - How to write good comments

        - Why comment should not be written

        - Links: [[1](https://medium.freecodecamp.org/code-comments-the-good-the-bad-and-the-ugly-be9cc65fbf83), [2](https://dzone.com/articles/5-best-practices-commenting), [3](https://blog.codinghorror.com/code-tells-you-how-comments-tell-you-why/)]

      - #### [Strict Mode](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode)

      - #### [JavaScript’s Type System](http://2ality.com/2013/09/types.html)
        
        - Static Versus Dynamic

        - JS Types

        - Static Typing Versus Dynamic Typing
        
        - Static Type Checking Versus Dynamic Type Checking
        
        - Coercion
        
        - [An explanation of JavaScript’s weird type system](https://medium.com/dailyjs/the-why-behind-the-wat-an-explanation-of-javascripts-weird-type-system-83b92879a8db)

      - #### Primitive Values Versus Objects

        - [JavaScript Primitive vs. Reference Values](http://www.javascripttutorial.net/javascript-primitive-vs-reference-values/)

        - [The Difference Between Boolean Objects and Boolean Primitives in JavaScript](http://adripofjavascript.com/blog/drips/the-difference-between-boolean-objects-and-boolean-primitives-in-javascript.html)

      - #### undefined and null
        - [What’s the difference between Null & Undefined?](https://codeburst.io/javascript-whats-the-difference-between-null-undefined-37793b5bfce6)

      - #### [Equality Operators: === Versus ==](https://codeburst.io/javascript-showdown-vs-7be792be15b5)

      - #### [Logical Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_Operators)

      - #### [Truthy vs Falsy values](http://adripofjavascript.com/blog/drips/truthy-and-falsy-values-in-javascript.html)

      - #### [Bitwise Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators)

        - [Using JavaScript’s Bitwise Operators in Real Life](https://codeburst.io/using-javascript-bitwise-operators-in-real-life-f551a731ff5)

      - #### String
        - Unicode

          - Code Points

          - Size in bytes of a single char

          - [Unicode and javascript](http://speakingjs.com/es5/ch24.html)

        - Constructing Strings

        - Manipulation

        - Concatenation

      - #### Statements
      
        - Loops

          - for

          - while

          - do while

          - for in

        - if else

        - Switch

        - debugger statement
        
      - #### Functions ([details](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#roles-of-functions))

        - #### [Roles of functions](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#roles-of-functions)

        - #### [Defining Functions](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#defining-functions)

            - [Function Expressions](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#function-expressions)

            - [Function Declarations](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#function-declarations)

            - [The Function Constructor](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#the-function-constructor)

        - #### [Params vs Arguments](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#params-vs-arguments)
        - #### [Hoisting](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20%26%20closures/ch4.md)

        - #### [More Control over Function Calls: call(), apply(), and bind()](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#more-control-over-function-calls-call-apply-and-bind)

        - #### [Arguments Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/arguments)

        - #### [Closures](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#closures)

      - #### global/window object

        - [console](https://developer.mozilla.org/en-US/docs/Web/API/Console)
          
          - log
          
          - formatted output
        
        - [setTimeout](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/setTimeout)

          - [A good question on setTimeout](https://medium.com/coderbyte/a-tricky-javascript-interview-question-asked-by-google-and-amazon-48d212890703)

        - [setInterval](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/setInterval)

        - [clearInterval](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/clearInterval)

      - #### [Objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects)

        - Property Accessors ([Dot and square notation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Property_accessors))

        - [`this` in objects](http://2ality.com/2014/05/this.html)
          - Losing this When Extracting a Method
          - Functions Inside Methods Shadow this
          - Other [gotchas when using this](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)

        - [Inheritance](https://www.digitalocean.com/community/tutorials/understanding-prototypes-and-inheritance-in-javascript)

          - [Prototypal Chain](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)

          - Sharing Data Between Objects via a Prototype

          - Setting and Deleting Affects Only Own Properties

          - [Javascript inheritance by examples](http://2ality.com/2012/01/js-inheritance-by-example.html)

        - Object reflective methods

          - [.keys](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys)

          - Check out all the methods of Object [here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)

        - Accessors ([Getters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/get) and [Setters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/set))

        - [Property Attributes and Property Descriptors](http://2ality.com/2012/10/javascript-properties.html)

        - [Protecting Objects](http://2ality.com/2013/08/protecting-objects.html)

          - Sealing

          - Extensions

          - Freezing

          - Protection Is Shallow

      - #### Exception Handling

        - What Is Exception Handling?

        - Exception Handling in JavaScript

          - throw

          - [try-catch-finally](Languages  Edit  Advanced try...catch)

        - Error Constructors

        - Stack Traces
        
        - All these are explained [`here`](http://speakingjs.com/es5/ch14.html)

      - #### Arrays
        - Forms of objects

          > Arrays are list-like objects whose prototype has methods to perform traversal and mutation operations. Neither the length of a JavaScript array nor the types of its elements are fixed. Since an array's length can change at any time, and data can be stored at non-contiguous locations in the array, JavaScript arrays are not guaranteed to be dense; this depends on how the programmer chooses to use them. In general, these are convenient characteristics; but if these features are not desirable for your particular use, you might consider using typed arrays.

          Arrays cannot use strings as element indexes (as in an associative array) but must use integers. Setting or accessing via non-integers using bracket notation (or dot notation) will not set or retrieve an element from the array list itself, but will set or access a variable associated with that array's object property collection. The array's object properties and list of array elements are separate, and the array's traversal and mutation operations cannot be applied to these named properties.

        - Array Methods

          - [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)

          - [Reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)

          - [Filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)

          - [forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)

        - [mutating and non-mutating methods](https://lorenstewart.me/2017/01/22/javascript-array-methods-mutating-vs-non-mutating/)

      - #### [Regular Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)

        - Quantifiers

        - Capture Groups

        - Flags

        - [.test](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/test)

        - [.match](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match)

        - [.exec](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/exec)

        - [A simple tool to play with regex](http://regexr.com/)

        - [Javascript regex in depth](http://speakingjs.com/es5/ch19.html)

      - #### [Date object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)

        - Epoch time

        - [Understanding Date and Time in JavaScript](https://www.digitalocean.com/community/tutorials/understanding-date-and-time-in-javascript)

      - #### [JSON](https://www.json.org/)

        - [Working with JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)

        - [parse](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/parse)

        - [stringify](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify)

        - [difference between objects and JSON](https://stackoverflow.com/questions/8294088/javascript-object-vs-json)

    - #### Modules
      - [JavaScript Modules: A Beginner’s Guide](https://medium.freecodecamp.org/javascript-modules-a-beginner-s-guide-783f7d7a5fcc)

      - [In-depth](http://exploringjs.com/es6/ch_modules.html)

    - #### Shallow copy and Deep Copy

      - [Copying objects in javascript](https://scotch.io/bar-talk/copying-objects-in-javascript)

      - How to deep copy

      - Why it's required

    - #### [instanceof](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/instanceof), [typeof](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/typeof), [new](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new)

      - [More about 'new'](https://codeburst.io/javascript-for-beginners-the-new-operator-cee35beb669e)

    - #### Pure, total and partial functions
      - [What are pure functions and why use them?](https://medium.com/@jamesjefferyuk/javascript-what-are-pure-functions-4d4d5392d49c)

      - [Pure versus impure functions](https://toddmotto.com/pure-versus-impure-functions)

      - Partial Functions

      - Functional perspective

        - [Decoupling methods from their objects](https://hackernoon.com/functional-javascript-decoupling-methods-from-their-objects-aa3ca13d7ae8)

        - [Function Composition For Every Day Use.](https://hackernoon.com/javascript-functional-composition-for-every-day-use-22421ef65a10)

      - Why it's better than loops

        - [map vs forEach vs for](https://ryanpcmcquen.org/javascript/2015/10/25/map-vs-foreach-vs-for.html)

        - [Rethinking JavaScript: Death of the For Loop](https://hackernoon.com/rethinking-javascript-death-of-the-for-loop-c431564c84a8) (Also read comments from the author for more context and why loops are a better choice in some cases)

    - #### Built In Modules

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

  - ## ES6
    - #### [Let](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let) and [Const](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const)
      - Lexical Scope vs Function Scope
      - Why const?
      - Only references are const
      - Temporal Dead Zone
      - [Variables and scoping in ECMAScript 6](http://2ality.com/2015/02/es6-scoping.html)
    - #### [Template Literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)
    - #### [Arrow Functions Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
      - this is lexical instead of bind
      - [versus normal functions](http://exploringjs.com/es6/ch_arrow-functions.html#sec_arrow-func-vs-normal-func)
    - #### [for-of](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of)
    
    - #### [default parameters](https://css-tricks.com/using-default-parameters-es6/)
    
    - #### [Named Params](http://exploringjs.com/es6/ch_parameter-handling.html#sec_named-parameters)
    
    - #### [Rest Params](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters)
    
    - #### [Tagged Templates](https://medium.freecodecamp.org/es6-tagged-template-literals-48a70ef3ed4d)
    
    - #### [De-structuring Assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)
    
    - #### [Shorthand Properties](https://www.eventbrite.com/engineering/learning-es6-enhanced-object-literals/)
    
    - #### [ES6 Modules](http://exploringjs.com/es6/ch_modules.html)

      - CJS

      - AMD

    - #### [Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)

      - [then](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/then)

      - [catch](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/catch)

      - [finally](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/finally)

      - [all](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/all)

    - #### [Classes in ES6](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

      - How it's same as new Function

      - [In-Depth](http://exploringjs.com/es6/ch_classes.html)

    - #### [Computed Object properties](https://www.eventbrite.com/engineering/learning-es6-enhanced-object-literals/)
    - #### [Object.assign](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign)
    - #### [Async/Await](http://exploringjs.com/es2016-es2017/ch_async-functions.html) (Promises)
      - How it's based on Promises
    - #### [Symbols](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol)
    - #### [Maps](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map) and [WeakMaps](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap)
    - #### [Sets](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set) and [WeakSets](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakSet)
    - #### [Iterator Protocol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Iteration_protocols#The_iterator_protocol)
    - #### [Proxy](https://codeburst.io/understanding-javascript-proxies-by-examining-on-change-library-f252eddf76c2)
    - #### [Generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator)
    - #### [Iterators and generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Iterators_and_Generators)
    - #### [function*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function*)
    - #### [yield](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield)
    - #### [yield*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield*)
  - ## Style Guides
    - #### [AirBnB](https://github.com/airbnb/javascript)
      - [Breathing air into AirBnB’s JavaScript Style Guide](https://medium.freecodecamp.org/adding-some-air-to-the-airbnb-style-guide-3df40e31c57a)
      
      - [5 JavaScript Style Guides — Including AirBnB, GitHub, & Google](https://codeburst.io/5-javascript-style-guides-including-airbnb-github-google-88cbc6b2b7aa)
    - #### [Google](https://google.github.io/styleguide/jsguide.html)
    - #### [Standard JS](https://standardjs.com/rules.html)

- # Frontend

  - ## HTML5

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

  - ## CSS3
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

      - [Autoprefixer](https://autoprefixer.github.io/)

    - [CSS Basics](https://www.youtube.com/watch?v=s7ONvIgOWdM&list=PLqGj3iMvMa4IOmy04kDxh_hqODMqoeeCy) Videos

    - [CSS Positioning](https://www.youtube.com/watch?v=kejG8G0dr5U&list=PLqGj3iMvMa4L731ispRfGAabXeRpM4RL6) Videos

  - ## [JSON](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON) as [Data Exchange format](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)

  - ## Javascript Elements for Frontend
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

  - ## React ([details](https://github.com/PestoTech/curriculum/tree/master/React#react))

  - ## Redux

    - [Official Docs](https://redux.js.org/)

    - [When to use redux?](https://medium.com/dailyjs/when-do-i-know-im-ready-for-redux-f34da253c85f)

      - [You MIGHT Not Need Redux](https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367)
      (By the creator of Redux: Dan Abramov)

  - ## Router

    > React Router is a collection of navigational components that compose declaratively with your application.

    - [Official Docs](https://reacttraining.com/react-router/web/guides/philosophy)

    - [A Simple React Router v4 Tutorial](https://medium.com/@pshrmn/a-simple-react-router-v4-tutorial-7f23ff27adf)

  - ## Storage
    - [Cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)

    - [IndexDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)

    - [WebStorage](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API)

    - [Cache API](https://developer.mozilla.org/en-US/docs/Web/API/Cache#Browser_compatibility)

  - ## Localisation/Internationalization
    - Read [this](https://www.w3.org/International/questions/qa-i18n) to get an overview of what they are and the difference between them.

  - ## [Accessibility](https://developers.google.com/web/fundamentals/accessibility/)
  
    - [w3 docs](https://www.w3.org/WAI/intro/accessibility.php)

    - [Course on Udacity](https://in.udacity.com/course/web-accessibility--ud891)

  - ## Security
  
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

- ## Tooling
  - [Build Tools](http://www.lihaoyi.com/post/WhatsinaBuildTool.html) and Bundlers
    - [NPM Scripts](https://docs.npmjs.com/misc/scripts)

      - [NPM](https://deliciousbrains.com/npm-build-script/) [scripts]() [as a build tool](https://deliciousbrains.com/npm-build-script/)

    - [Gulp](https://github.com/gulpjs/gulp/blob/v3.9.1/docs/API.md)

    - [JavaScript build tools and automation systems](https://hackernoon.com/javascript-build-tools-and-automation-systems-9589c5c91ebe)

    - [Choosing a JavaScript build tool: to config or not config](https://dev.to/netlify/choosing-a-javascript-build-tool-to-config-or-not-config-2ia8)

    - [Making a sense out of build tools](https://medium.freecodecamp.org/making-sense-of-front-end-build-tools-3a1b3a87043b)

    - [Module Bundling](https://medium.freecodecamp.org/javascript-modules-part-2-module-bundling-5020383cf306)

    - [Webpack](https://github.com/PestoTech/curriculum/tree/master/Webpack#webpack)

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

- ## Network, Protocols, Browsers
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

- ## Backend
  - ### Node
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

    **Node Resources**

    - [Official Docs](https://nodejs.org/docs/latest/api/)

    - [Awesome NodeJS](https://github.com/sindresorhus/awesome-nodejs)

  - ### Express

    - [MVC](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller) (Model, View, Controller)

      - [Model-View-Controller (MVC) Explained Through Ordering Drinks At The Bar](https://medium.freecodecamp.org/model-view-controller-mvc-explained-through-ordering-drinks-at-the-bar-efcba6255053)

    - [morgan](https://github.com/expressjs/morgan) - log each request
    - [cors](https://github.com/expressjs/cors) - enable CORS
    - [body-parser](https://github.com/expressjs/body-parser) - Node.js body parsing middleware
    - [Helmet.js](https://github.com/helmetjs/helmet) - help secure Express apps with various HTTP headers

    **Express Resources**

    - [Official Docs](https://expressjs.com/en/4x/api.html)

    - [Github Repo](https://github.com/expressjs/express)

  - ### Mongo

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

    **Mongo Resources**

    - [MongoDB Docs](https://docs.mongodb.com/)

    - [MongoDB basics](https://university.mongodb.com/courses/M001/about)
    - [MongoDB for Node.js Developers](https://university.mongodb.com/courses/M101JS/about)
    - [Aggregation framework](https://university.mongodb.com/courses/M121/about)

  - #### Auth
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

  - #### APIs

    - Rest

    - #### GraphQL

      #### Understand

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

      #### GraphQL Resources

      - [Official Docs](http://graphql.org/) [Read the **Learn** Segment for most of **Understand** Section]

      - Articles

        - [So what’s this GraphQL thing I keep hearing about?](https://medium.freecodecamp.org/so-whats-this-graphql-thing-i-keep-hearing-about-baf4d36c20cf)

        - [REST APIs are REST-in-Peace APIs. Long Live GraphQL.](https://medium.freecodecamp.org/rest-apis-are-rest-in-peace-apis-long-live-graphql-d412e559d8e4)
        - [The Anatomy of a GraphQL Query](https://dev-blog.apollodata.com/the-anatomy-of-a-graphql-query-6dffa9e9e747)
        - [GraphQL vs. REST](https://dev-blog.apollodata.com/graphql-vs-rest-5d425123e34b)
        - [Full-stack React + GraphQL Tutorial](https://dev-blog.apollodata.com/full-stack-react-graphql-tutorial-582ac8d24e3b)
        - [The GraphQL stack: How everything fits together](https://dev-blog.apollodata.com/the-graphql-stack-how-everything-fits-together-35f8bf34f841)
        - [Tutorial: How to build a GraphQL server](https://dev-blog.apollodata.com/tutorial-building-a-graphql-server-cddaa023c035)
        - [GraphQL schema stitching](https://dev-blog.apollodata.com/graphql-schema-stitching-8af23354ac37)
        - [GraphQL Fragments are the Best Match for UI Components](https://blog.manifold.co/graphql-fragments-are-the-best-match-for-ui-components-72b8f61c20fe)
        - [Five Common Problems in GraphQL Apps (And How to Fix Them)](https://medium.freecodecamp.org/five-common-problems-in-graphql-apps-and-how-to-fix-them-ac74d37a293c)
      - Books
        - Learning GraphQL and Relay - Samer Buna

      #### Courses

      - Websites and Videos

        - [How to GraphQL](https://www.howtographql.com/)

      - **[Awesome GraphQL](https://github.com/chentsulin/awesome-graphql)**

- ## [Testing](https://github.com/PestoTech/curriculum/tree/master/Testing#testing)
  
  - ### [Test Driven Development (TDD)](https://github.com/PestoTech/curriculum/tree/master/Testing#tdd)

  - ### Jest, Enzyme

    - Unit Testing

    - Snapshot Testing

    - E2E Testing

- # Deployment

  - ## Services

    - [Heroku](https://www.heroku.com/)

    - AWS Compute Engine

    - Serverless

  - ## Production

    - Secrets in Version Control Systems
    
    - Caching
    
    - CDNs
    
    - Horizontal / Vertical Scaling
    
    - Profilers
    
    - Load Balancers
    
    - Data Sharding/Duplication
    
    - Backups

- ## Ethical Concerns of Software Production and Engineering

- ## Tech Soft Skills

  - Take Responsibility/Ownership

  - Standups
  
  - WIP and when a PR is ready
  
  - Expectation of quality work
  
  - Over communicating
  
  - Spelling things right. Use spell-check editor in VSCode.
