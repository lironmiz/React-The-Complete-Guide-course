<a name="readme-top"></a>
<h1 align="center"> 🔱 React-The-Complete-Guide-course 🔱</h1>

<img src="https://i.imgur.com/dBaSKWF.gif" height="50" width="100%">

Dive in and learn React.js from scratch! Learn Reactjs, Hooks, Redux, React Routing, Animations, Next.js and way more!

This course will teach you React.js in a practice-oriented way, using all the latest patterns and best practices you need. You will learn all the key fundamentals as well as advanced concepts and related topics to turn you into a React.js developer.

This is a huge course because it really covers EVERYTHING you need to know and learn to become a React.js developer!

No matter if you know nothing about React or if you already got some basic React knowledge (not required but also not a problem), you will get tons of useful information and knowledge out of this course!

My goal with this course is to ensure that you feel confident working with React, so that you can apply for React jobs, use it in your own projects or simply enhance your portfolio as a developer - whatever your goal is: This course gets you there!


<!-- Table of Contents -->
<details>

<summary>

# :notebook_with_decorative_cover: Table of Contents

</summary>

- [The Graduation Certificate](#star2-the-graduation-certificate)
- [Course Material](#books-course-material) 
- [Course Summary](#alien-course-summary) 
- [Contact](#handshake-contact)
- [About the authors](#telephone-about-the-authors)

</details>  

<!-- The Graduation Certificate -->


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Course Material -->
# :books: Course Material

![image](https://user-images.githubusercontent.com/91504420/235323079-183ad9fc-0092-4d86-862b-54ed22ba5db2.png)

  + JavaScript Refresher
  + Let and Const 
  + Arrow Functions
  + React 
  + JSX
  + React components 
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- The Course Summary -->

# :alien: Course Summary

## 1. TABLE OF CONTENTS
  - [1. TABLE OF CONTENTS](#1-table-of-contents)
  - [2. JAVASCRIPT REFRESHER](#2-javascript-refresher)
  - [3. REACT](#3-react)
  - [4. HOW TO START REACT PROJECT](#4-how-to-start-react-project)
  - [5. JSX](#5-JSX)
  - [6. HOW REACT WORKS](#6-how-react-works)
  - [7. REACT COMPONENTS](#7-react-components)
  - [8. STYLE REACT COMPONENTS](#8-style-react-components)
## 2. JAVASCRIPT REFRESHER

![RonBurgundyAnchormanGIF](https://user-images.githubusercontent.com/91504420/235323465-d11b4618-a3fa-4c35-a0c1-976644591894.gif)

In JavaScript, let and const are used to declare variables, but they differ in their behavior.

let is used to declare variables that are block-scoped, meaning that they are only accessible within the block of code they are defined in, such as within a function or a loop. A variable declared with let can be reassigned a new value, but cannot be redeclared within the same block.

const, on the other hand, is used to declare variables that are also block-scoped, but their value cannot be reassigned. A variable declared with const must be initialized at the time of declaration, and cannot be left uninitialized.

In summary, use let when you need to declare a variable that can be reassigned and use const when you need to declare a variable whose value should not be changed.
 
### Arrow function

![CoolMinionsGIF](https://user-images.githubusercontent.com/91504420/235323658-6d56efb9-5050-4861-9753-f7376616c745.gif)

In JavaScript, arrow functions provide a shorthand syntax for writing function expressions. They are commonly used in modern JavaScript frameworks and libraries.

Here are some key points about arrow functions:

Arrow functions have a concise syntax using an arrow (=>) symbol.
They do not have their own this value and instead inherit it from the enclosing lexical scope.
Arrow functions are always anonymous and cannot be named.
If the function only has one parameter, the parentheses around the parameter can be omitted.
If the function body consists of a single expression, the curly braces and return keyword can be omitted.

```
// Regular function
function add(a, b) {
  return a + b;
}

// Arrow function
const add = (a, b) => a + b;
```

In summary, arrow functions are a concise and powerful syntax for writing function expressions in JavaScript, and are particularly useful for writing inline functions, callbacks, and event handlers.

### Exports & Imports 

![EvilSpongebobGIF](https://user-images.githubusercontent.com/91504420/235324840-9d3640a1-99ed-4cec-bc53-5715c930ff0a.gif)

In JavaScript, exports and imports are used to enable modules to be shared across multiple files. They are commonly used in modern JavaScript development, especially with the advent of ES6 modules.

Here are some key points about exports and imports:

exports is used to define what parts of a module should be made available for use in other files.
exports can be assigned values directly, or used to attach properties to an object that can then be exported.
import is used to bring in parts of a module that have been exported in another file.
import statements must be placed at the top of a file, before any other code is executed.
import statements can specify which parts of a module to import, and can use destructuring syntax to assign imported values to variables with different names.

```
// In module1.js
const value1 = 10;
const value2 = 20;

exports.value1 = value1;
exports.value2 = value2;

// In module2.js
import { value1, value2 } from './module1.js';

console.log(value1); // Output: 10
console.log(value2); // Output: 20
```

In summary, exports and imports are a powerful feature of modern JavaScript that enable modular and reusable code, and are an important tool for organizing code in larger applications.

## 3. REACT

![SoItBeginsRainingGIF](https://github.com/lironmiz/React-The-Complete-Guide-course/assets/91504420/13be2e05-d2f3-49d9-95cf-b0a9af2142ae)


React is a JavaScript library for building user interfaces. It is a declarative library, which means that you describe what you want your UI to look like, and React will figure out how to render it. This makes React very efficient and easy to use.e

React is also very scalable. It can be used to build small, single-page applications, or large, complex web applications. It is also very popular, and there is a large community of developers who are using and contributing to React.

Here are some of the benefits of using React:

Declarative: React is a declarative library, which means that you describe what you want your UI to look like, and React will figure out how to render it. This makes React very efficient and easy to use.
Scalable: React is very scalable. It can be used to build small, single-page applications, or large, complex web applications.
Popular: React is very popular, and there is a large community of developers who are using and contributing to React.
If you are looking for a JavaScript library for building user interfaces, React is a great option. It is efficient, scalable, and popular.

![image](https://github.com/lironmiz/React-The-Complete-Guide-course/assets/91504420/0d4c2225-2edd-4066-b6f6-4c39142fda0f)

## 4. HOW TO START REACT PROJECT

![ImaginationSpongebobSquarepantsGIF](https://github.com/lironmiz/React-The-Complete-Guide-course/assets/91504420/d75bee2e-c6c8-4a7b-9aa8-cee1b5a30f78)

+ Install Node.js and npm.\

+ Create a new directory for your project.

+ In the project directory, run the following command to create a new React project:

```
npx create-react-app my-app
```

+ This will create a new directory called my-app with all the necessary files for a React project.

+ To start the development server, run the following command:

```
cd my-app
npm start
```

+ This will start a development server on port 3000. You can open your browser and go to http://localhost:3000 to see your project.


+ To make changes to your project, edit the files in the src directory.

+ To start the development server again, run the following command:

```
npm start
```

+ To build your project for production, run the following command:

```
npm run build
```

This will create a build directory with all the files necessary to deploy your project.

## 5. JSX

![PrettyInnovativeStuffLadyDecadeGIF](https://github.com/lironmiz/React-The-Complete-Guide-course/assets/91504420/1a813f9c-2254-40e5-bde9-443a6f948cab)

JSX, short for JavaScript XML, is an extension to JavaScript that allows you to write HTML-like code inside of JavaScript files. JSX is a popular feature of React, a JavaScript library for building user interfaces.

JSX code is compiled into React elements, which are then rendered to the DOM. This makes it easy to write complex user interfaces without having to worry about the DOM directly.

## 6. HOW REACT WORKS

![ThatsHowThatWorksThatsHowItsDoneGIF](https://github.com/lironmiz/React-The-Complete-Guide-course/assets/91504420/a95b4f2b-3779-46c9-9170-f2ea8a94fee7)

React is a JavaScript library for building user interfaces. It is a declarative library, which means that you describe what you want your UI to look like, and React takes care of how to render it.

React uses a virtual DOM to represent the state of your UI. The virtual DOM is a lightweight representation of the actual DOM. When you make changes to your UI, React compares the virtual DOM to the actual DOM and only updates the parts of the actual DOM that have changed. This is called reconciliation.

React also uses a component-based architecture. Components are reusable blocks of code that can be used to build complex UIs. Components are easy to test and maintain, and they make it easy to scale your UI.

## 7. REACT COMPONENTS

![JagyasiniSinghFindnewjagGIF](https://github.com/lironmiz/React-The-Complete-Guide-course/assets/91504420/c3f1b869-8e57-4783-b0e3-b46eee4caadd)

eact components are the building blocks of a user interface in React, a popular JavaScript library for building user interfaces. In React, components are reusable and self-contained units of code that encapsulate a specific set of functionality and user interface elements.

Components in React can be thought of as custom HTML elements with associated behavior and state. They can be composed together to create complex user interfaces. React components can be either class-based components or function components, with the latter being the preferred approach in modern React development.

In the MyComponent.js file, you'll define your component. You can create a functional component or a class-based component, depending on your needs.

Functional Component Example:

```
import React from 'react';

function MyComponent() {
  return <div>Hello, World!</div>;
}

export default MyComponent;
```

Class-based Component Example:

```
import React from 'react';

class MyComponent extends React.Component {
  render() {
    return <div>Hello, World!</div>;
  }
}

export default MyComponent;
```

Step 3: Use the Component
To use your newly created component, open the src/App.js file in your project and import your component at the top of the file:

```
import React from 'react';
import MyComponent from './MyComponent';

function App() {
  return (
    <div>
      <h1>Welcome to my React App</h1>
      <MyComponent />
    </div>
  );
}

export default App;
```

## 8. STYLE REACT COMPONENTS

![FashionStyleGIF](https://github.com/lironmiz/React-The-Complete-Guide-course/assets/91504420/05a2e2f2-e224-4fea-bb9b-0d8fb0ff0edf)

Styling React components can be done in several ways. Here are a few common approaches:

Inline Styles: You can apply styles directly to your React components using inline styles. Inline styles are defined as JavaScript objects, where the keys are the CSS properties, and the values are the corresponding styles.
jsx

```
import React from 'react';

const MyComponent = () => {
  const styles = {
    backgroundColor: 'blue',
    color: 'white',
    padding: '10px',
    borderRadius: '5px'
  };

  return <div style={styles}>Hello, World!</div>;
};

export default MyComponent;

```

CSS Stylesheets: You can create a separate CSS file and import it into your React component. Define CSS rules in the file, and the styles will be applied to the corresponding component.

```
// styles.css
.myComponent {
  background-color: blue;
  color: white;
  padding: 10px;
  border-radius: 5px;
}

// MyComponent.jsx
import React from 'react';
import './styles.css';

const MyComponent = () => {
  return <div className="myComponent">Hello, World!</div>;
};

export default MyComponent;

```
CSS Modules: CSS Modules allow you to write CSS styles locally for each component, avoiding global style conflicts. When you import a CSS module, you get an object with unique names for each style.

```
// MyComponent.module.css
.myComponent {
  background-color: blue;
  color: white;
  padding: 10px;
  border-radius: 5px;
}

// MyComponent.jsx
import React from 'react';
import styles from './MyComponent.module.css';

const MyComponent = () => {
  return <div className={styles.myComponent}>Hello, World!</div>;
};

export default MyComponent;

```

CSS-in-JS Libraries: There are popular CSS-in-JS libraries like styled-components, Emotion, and CSS Modules with TypeScript that allow you to write CSS directly within your JavaScript/JSX code. These libraries provide powerful features for dynamic styling and easy component-specific styles.

```
import React from 'react';
import styled from 'styled-components';

const StyledComponent = styled.div`
  background-color: blue;
  color: white;
  padding: 10px;
  border-radius: 5px;
`;

const MyComponent = () => {
  return <StyledComponent>Hello, World!</StyledComponent>;
};

export default MyComponent;

```

<!-- Contact -->
# :handshake: Contact

<p align="left">
<a href="https://twitter.com/liron_mizrahi" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="liron_mizrahi" height="50" width="60" /></a>
<a href="https://instagram.com/liron.mizrhai1234" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="liron.mizrhai1234" height="50" width="60" /></a>
<a href="https://www.linkedin.com/in/%D7%9C%D7%99%D7%A8%D7%95%D7%9F-%D7%9E%D7%96%D7%A8%D7%97%D7%99-1050b421a/">
  <img align="left" alt="liron LinkedIN" height="50" width="60" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/linkedin.svg" />
</a>
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- About the authors -->
## :telephone: About the authors

 - Liron Mizarhi - Navy soldier and programmer

<p align="right">(<a href="#readme-top">back to top</a>)</p>
