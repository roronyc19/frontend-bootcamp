# Frontend Bootcamp

## Welcome

In this two-day workshop you'll learn the basics of frontend development while building a working web app.

The first day provides an introduction to the fundamentals of the web: HTML, CSS and JavaScript. This is targeted at new and experienced developers alike. On the second day we'll dive into more advanced topics like TypeScript, state management, and testing. While the examples should be accessible to anyone, you'll get the most out of it if you have some prior experience with programming and web technologies.

## Getting set up

### 1. Required software

Before starting, make sure your computer has up-to-date versions of the following installed:

- [Node/NPM](https://nodejs.org/en/) (choose the **LTS** option, which should be version 10)
- [Git](https://git-scm.com/downloads)
- [Visual Studio Code](https://code.visualstudio.com)
  - If using a Mac, also follow [these steps](https://code.visualstudio.com/docs/setup/mac#_launching-from-the-command-line) to install the `code` terminal command.
  - If you already had VS Code installed, check for updates!
- React Developer Tools for [Chrome](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/react-devtools/)

### 2. Installing and opening the project

- Open VS Code and then press `` ctrl + ` `` (backtick, in top left corner of keyboard) to open the built-in terminal
- Use the `cd` (change directory) command to find an appropriate place for your code
- Type `git clone https://github.com/Microsoft/frontend-bootcamp.git` into the terminal to pull down a copy of the workshop code
- Type `cd frontend-bootcamp` to change your current directory to the bootcamp folder
- Type `npm install` to install all of the project dependencies
- Type `code -r .` to open the bootcamp code in VS Code
  > If on a Mac, be sure you've followed [these steps](https://code.visualstudio.com/docs/setup/mac#_launching-from-the-command-line) first to make the `code` command available.

### 3. Run the "inner loop" build

At this point, your VS Code window should look something like this:

<img src="https://user-images.githubusercontent.com/1434956/53654442-9c379400-3c02-11e9-8768-d19e092b606d.png" width=500 />

To start the dev "inner loop," run:

```
npm start
```

This will load the site shown below.

<img src="https://user-images.githubusercontent.com/1434956/53656239-88426100-3c07-11e9-8456-e3d958aa4def.png" width=500 />

### 4. Lesson Structure

1. Demos will either be via CodePen (Steps 1, 2 and 3) or done in the step folder. Follow the step README to walkthrough the demo.

2. Much like demos, exercises are done via CodePen or in the project step folders. These exercises will give you an opportunity to try what was demonstrated in the first step.

## What to expect

For each lesson, the presenter will walk through some demo code to teach core concepts about the topic. Don't worry about writing code at this point. Just follow along via the readmes linked below.

Most lessons also have an exercise portion. Exercise instructions are usually found in the readme for each step's "exercise" folder.

### Day one

Day one covers the basics of HTML, CSS and JavaScript, as well as an introduction to React and TypeScript.

1. [Introduction to HTML](step1-01)
2. [Introduction to CSS](step1-02)
3. [Introduction JavaScript](step1-03)
4. [Introduction to React](step1-04)
5. [React Components](step1-05)
6. [State-driven UI](step1-06)
7. [Types and UI-driven state](step1-07)

### Day two

1. [TypeScript basics](step2-01)
2. [Fluent UI component library](step2-02)
3. [Theming and styling](step2-03)
4. [React Context](step2-04)
5. [Redux: Store](step2-05)
6. [Redux: React binding](step2-06)

### Bonus content

- [Redux: Service calls](bonus-servicecalls)
- [Testing with Jest](bonus-jest)

## Additional resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/)
- [React Docs](https://reactjs.org/docs/getting-started.html)
- [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
