# Testing
- ## TDD

  > Something that is untested is broken.

  ### Understand

  - Why testing is required?

  - Static (code reviews, inspection, linting) vs. dynamic testing (running tests suites)

  - Black box and White Box testing

  - #### Testing Levels
    
    - Unit Testing
    
    - Integration Testing
    
    - System Testing
    
    - Alpha and Beta Testing
    
    - Functional and Non-Functional Testing

  - Mocks, Stubs, Fakes, Spies

  - Code Coverage Reports

  ### Testing Overview

  Software testing is one of the key parts of developing any application. Tests are where you write code to test your code. This helps prevent bugs and promotes cleaner code. It is also what allows us to use continuous deployment systems to deploy code confidently. With good test coverage, you no longer have to go through any manually click around to test your changes every time you push new code.

  - [Software Testing](https://en.wikipedia.org/wiki/Software_testing) [Read the portions mentioned in the Understand section]

  - [Open Lecture by James Bach on Software Testing](https://www.youtube.com/watch?v=ILkT_HV9DVU) [Video]

  - [Understanding how software testing works and what to test](https://stackoverflow.com/questions/3065485/understanding-how-software-testing-works-and-what-to-test)

  - [Test Doubles — Fakes, Mocks and Stubs.](https://blog.pragmatists.com/test-doubles-fakes-mocks-and-stubs-1a7491dfa3da)

  - [Mocks Aren't Stubs](https://martinfowler.com/articles/mocksArentStubs.html)

  ### Frontend Testing

  - [Unit Testing Front-End](https://medium.com/front-end-hacking/unit-testing-front-end-38b9bf1de079)

  - [The Front-End Test Pyramid: How to Rethink Your Testing](https://medium.freecodecamp.org/the-front-end-test-pyramid-rethink-your-testing-3b343c2bca51)

  - [Testing Your Frontend Code](https://hackernoon.com/testing-your-frontend-code-part-i-introduction-7e307eac4446) [Part 1 to 5]

  - [“Nobody cares about tests in front-end” Really?!](https://medium.com/rd-shipit/nobody-cares-about-tests-in-front-end-really-d1c8db7ba59d)

  - [A Skeptics Guide to Frontend Testing](https://codeburst.io/a-skeptics-guide-to-frontend-testing-part-1-5de4806ad300) [Part 1 to 3]

  ### Unit Tests

  Good unit tests should read like a set of instructions for the tested piece of code. A reader should be able to read through the tests and know immediately what the tested code is supposed to do, without having to look at the code itself.

  - [Unit testing Node.js with Tape](https://hackernoon.com/unit-testing-node-js-38cf2b7e1a41)

  - [My honest opinion about Unit Testing](https://hackernoon.com/my-honest-opinion-about-unit-testing-84eee5e893ad)

  - [5 Questions Every Unit Test Must Answer](https://medium.com/javascript-scene/what-every-unit-test-needs-f6cd34d9836d)

  ### Test Driven Development

  - [TDD the RITE Way](https://medium.com/javascript-scene/tdd-the-rite-way-53c9b46f45e3)
  
  - [Learn Test Driven Development](https://github.com/dwyl/learn-tdd) [Extensive Resource]

  ### Testing and TDD in JavaScript

  Every language has different ways to support the same principles with its own set of best-practices and common steps. Please focus on this part since most of our projects are made in JavaScript.

  Also, libraries such as React have their own standards and best practices in testing. We'll include that soon.

  - A Gentle Introduction To JavaScript TDD [[Part 1](https://jrsinclair.com/articles/2016/gentle-introduction-to-javascript-tdd-intro/), [Part 2](https://jrsinclair.com/articles/2016/gentle-introduction-to-javascript-tdd-ajax), [Part 3](https://jrsinclair.com/articles/2016/gentle-introduction-to-javascript-tdd-html-dom)]

  - [What is a Javascript Test ?](https://blog.kentcdodds.com/but-really-what-is-a-javascript-test-46fe5f3fad77)

  - [An Overview of JavaScript Testing in 2017](https://medium.com/powtoon-engineering/a-complete-guide-to-testing-javascript-in-2017-a217b4cd5a2a)

  - [JavaScript unit testing frameworks: Comparing Jasmine, Mocha, AVA, Tape and Jest](https://raygun.com/blog/javascript-unit-testing-frameworks/)

  - Udacity's [JavaScript Testing](https://in.udacity.com/course/javascript-testing--ud549) (UD549) [MOOC]

  ### Code Coverage

  - [The Importance of Code Coverage](https://blog.cloudboost.io/the-importance-of-code-coverage-9b4d513f39b4)

  ## Pro Tips:

  ### Test your contract

  A good test should only test it's contract with the other pieces of software that will use that piece of code. The test should NOT be testing a piece of codes implementation.

  If tests are designed this way, you should be able to refactor any line of code in your implementation without having to refactor your tests.

  ## Anti-Patterns

  ### Logic in the test assertion

  You should avoid adding logic whenever possible in the assertion part of your unit tests. This not only makes your tests harder to read but it also makes your test code more likely to have a bug, and therefore not actually test the original code properly.

  - [5 Common Misconceptions About TDD & Unit Tests](https://medium.com/javascript-scene/5-common-misconceptions-about-tdd-unit-tests-863d5beb3ce9)

- ## Jest, Enzyme
  - #### [Expect](https://facebook.github.io/jest/docs/en/expect.html), [it](https://facebook.github.io/jest/docs/en/api.html#testname-fn-timeout), and [matchers](https://facebook.github.io/jest/docs/en/using-matchers.html)

  - #### Unit Testing

  - #### Snapshot Testing

    - [Snapshot testing React Components with Jest](https://hackernoon.com/snapshot-testing-react-components-with-jest-744a1e980366)

    - [Testing React Apps](https://facebook.github.io/jest/docs/en/tutorial-react.html)

    - [Testing React components with Jest and Enzyme](https://hackernoon.com/testing-react-components-with-jest-and-enzyme-41d592c174f)

    - [How to Snapshot Test Everything in Your Redux App With Jest](https://hackernoon.com/how-to-snapshot-test-everything-in-your-redux-app-with-jest-fde305ebedea)

    - [Video] [Snapshot testing - Anna Doubkova, React London 2017](https://www.youtube.com/watch?v=sCbGfi40IWk)
    
    - [Video] [Jest Snapshots and Beyond - React Conf 2017](https://www.youtube.com/watch?v=HAuXJVI_bUs)

  - #### E2E Testing
    - e2e or end-to-end or UI testing is a methodology used to test whether the flow of an application is performing as designed from start to finish. In simple words, it is testing of your application from the user endpoint where the whole system is a blackbox with only the UI exposed to the user.

    - [Why End-to-End Testing is Important for Your Team](https://medium.freecodecamp.org/why-end-to-end-testing-is-important-for-your-team-cb7eb0ec1504)

    - [End-to-end Tests that Don’t Suck with Puppeteer](https://ropig.com/blog/end-end-tests-dont-suck-puppeteer/)

    - [Tutorial: User Interface Testing with Jest and Puppeteer](https://www.valentinog.com/blog/ui-testing-jest-puppetteer/)

    - [A Guide to Automating & Scraping the Web with JavaScript](https://codeburst.io/a-guide-to-automating-scraping-the-web-with-javascript-chrome-puppeteer-node-js-b18efb9e9921)

    - [Test React applications using Enzyme & Jest](https://www.youtube.com/watch?v=8Ww2QBVIw0I)