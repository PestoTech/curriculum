# Setting up environment

- ## Z Shell
  - Z Shell (aka zsh) is a drop-in replacement for your default bash shell. It does everything bash can do and more. Some nice improvements over bash are improved autocomplete, syntax highlighting and plugins via Oh My Zsh.

  - [Install it and Oh My Zsh by following the instructions here.](https://github.com/robbyrussell/oh-my-zsh)

  - [Few pro tip zsh features that you might not know about](https://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692).

  - #### Extensions

    - Autocomplete

    - git

    - jump

- ## Editor

  - ### VSCode

    > A software engineer's text editor of choice is somewhat just a personal preference. There isn't necessarily one right answer. However, to standardize our training and make it easier to collaborate, everyone is required to use VSCode.

    Visual Studio Code (VSCode) is our current text editor of choice. It is lightweight and easily extendable. It is built and maintained by Microsoft so it has really good native TypeScript support and is updated every month.

    [Download it here](https://code.visualstudio.com/)

    Install the following extensions from VSCode's extension marketplace. As with anything you install, you should take the time to read the documentation so that you know why each extension is useful.

    - #### Extensions
      - [Top JavaScript VSCode Extensions for Faster Development](https://codeburst.io/top-javascript-vscode-extensions-for-faster-development-c687c39596f5)

      - [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify)/ [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

      - [TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)

      - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

      - [GraphQL](https://marketplace.visualstudio.com/items?itemName=kumar-harsh.graphql-for-vscode)

      - [Color Picker](https://marketplace.visualstudio.com/items?itemName=anseki.vscode-color)

      - [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

      - [Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)

      - [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)

    - #### Additional Resources
      - [Visual Studio Code Can Do That?](http://vscodecandothat.com/)

      - [VSCode Docs](https://code.visualstudio.com/docs) [ Read the **Getting Started** and **Node/JS** sections ]

      - [VS Code Tips and Tricks](https://code.visualstudio.com/docs/getstarted/tips-and-tricks)

      - [How to debug ES6 NodeJS with VSCode](https://medium.com/@katopz/how-to-debug-es6-nodejs-with-vscode-8d00bd6c4f94)

      - [VS Code Extensions using CodeLens](https://medium.com/@waderyan_/vs-code-extensions-using-codelens-f0f452b1dd8b)

      - [Multiple Fonts: Alternative to Operator Mono in VSCode](https://medium.com/@zamamohammed/multiple-fonts-alternative-to-operator-mono-in-vscode-7745b52120a0)

      - [Live edit and debug your React apps directly from VS Code — without leaving the editor](https://medium.com/@auchenberg/live-edit-and-debug-your-react-apps-directly-from-vs-code-without-leaving-the-editor-3da489ed905f)

      - [Configure ESLint, Prettier, and Flow in VS Code for React Development](https://hackernoon.com/configure-eslint-prettier-and-flow-in-vs-code-for-react-development-c9d95db07213)

      - [Debugging React Like a Champ with VSCode](https://hackernoon.com/debugging-react-like-a-champ-with-vscode-66281760037)

      - [VSCode for React Native](https://medium.com/react-native-training/vscode-for-react-native-526ec4a368ce)

      - [New in VS Code: Inline Change Review](https://medium.com/fhinkel/new-in-vs-code-inline-change-review-d43df04ea264)

  - #### Basic Vim (for Git Rebase and in-terminal editing)

    - Command Mode and Insert Mode

    - !

    - wq

    - dd

    - dw

    - %s

    - Explore these links if you want to know and learn more about vim
      - [Learning Vim: What I Wish I Knew](https://medium.freecodecamp.org/learn-linux-vim-basic-features-19134461ab85)

      - [Vim Adventures](https://vim-adventures.com/)

      - [openvim](http://www.openvim.com/tutorial.html)

    - [Here's](https://vim.rtorr.com/) a small cheat sheet for quick references

- ## Terminal and Commands

  - iTerm2 with Oh My ZSH with extensions and a good theme (macOS)

  - curl

  - grep command

  - ls/ll

  - ps

- ## Version Managers

  - ### Node Version Manager

    Node Version Manager (nvm for short) is used for managing the different versions of node and npm installed on your machine. It allows you to easily switch between versions so that you can always make sure you are using the same version as everyone else for every project. By keeping the version consistent across your local development environment, your teammates' development environment and the servers, you get consistent results and don't run into version mismatch related bugs.

    [Install nvm by following the instructions here.](https://github.com/creationix/nvm)

- ## Package Managers

  - [yarn](https://yarnpkg.com/lang/en/)

  - [npm](https://docs.npmjs.com/getting-started/what-is-npm)(along with [npx](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b))

  - #### [Homebrew (macOS)

    - Homebrew is the go-to package manager for MacOS. It makes it super easy to install and update all of your different development tools.

    - [Install Homebrew by following the instructions here.](https://brew.sh/)

    - To see how awesome Homebrew is, go ahead and install MongoDB on your system.
    
      - [Here are the instructions to do it manually.](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/#install-mongodb-community-edition-manually)

      - [Here is how you install it with Homebrew.](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/#install-mongodb-community-edition-with-homebrew)

          brew install mongodb

      Another super useful homebrew package is hub by github. It allows you to create pull requests from the command line using:

          git pull-request

      Download and install is via homebrew [here](https://hub.github.com/).

- ## Environment Variables and uses

  - [env](https://medium.freecodecamp.org/heres-how-you-can-actually-use-node-environment-variables-8fdf98f53a0a)

  - [dotenv](https://github.com/motdotla/dotenv)

  - How to set cross platform ENVs

    - [crossenv](https://github.com/kentcdodds/cross-env)