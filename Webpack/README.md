# [Webpack](https://webpack.js.org/concepts/)

## Understand

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


## Resources

- [Web Tooling and Automation](https://in.udacity.com/course/web-tooling-automation--ud892) [Udacity's Course]

- [Webpack.org](https://webpack.js.org/concepts/)
- [Modern JavaScript Explained For Dinosaurs](https://medium.com/the-node-js-collection/modern-javascript-explained-for-dinosaurs-f695e9747b70)
- [How it feels to learn JavaScript in 2016](https://hackernoon.com/how-it-feels-to-learn-javascript-in-2016-d3a717dd577f)
- [Survive JS Webpack](https://survivejs.com/webpack/) - [Book]