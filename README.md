# Assignment-Intro

## Q.What is react ?
- React is a JavaScript library for building user interfaces. It's developed and maintained by Facebook,

## Q.Who made react ?
- React was created by Jordan Walke, a software engineer at Facebook.

## Q.What is babel ?
- Babel is a tool that allows developers to use new JavaScript features today by transpiling the 

## Q.How does Babel convert html code in react into valid code ?
- Babel takes HTML written in JSX (Javascript XML)  syntax and converts it into standard

## Q.What is react DOM used for ? Written an example
- ReactDOM is a package provided by React that provides a low level API for building user interfaces.
 ```
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FlexBoxInReact
    </title>
    <style>
        
        #parent2{
            display: flex;
            border: 2px solid black;
            background-color: #FFE4C4;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }
        
       
        
    </style>
</head>
<body>
    <div id="root"></div>
</body>
</html>
<script src="https://www.unpkg.com/react@18.2.0/umd/react.development.js"></script>
<script src="https://www.unpkg.com/react-dom@18.2.0/umd/react-dom.development.js"></script>

<script>

    let element=React.createElement("div",{id:"container",class:"main"},[
    React.createElement("h3",{},"Learning react"),
    React.createElement("p",{},"Day-2"),
    React.createElement("Button",{},"Click me")
    ])

    let reactRoot=ReactDOM.createRoot(document.getElementById("root"))

    reactRoot.render(element)

</script>
 ```

 ## Q.What are the packages that you need to import for react to work with?
- A.You only need to import these three libraries.
    1.React: The core library for building user interfaces in React.
    2.ReactDOM: Provides the ability to render instances of React components into the DOM.
    3.Babel:Helps transpile modern JavaScript (JSX, ES6+) into browser-compatible code.

## Q.How do you add react to a web application ?
- You can use npm or yarn package manager to install react and its dependencies by running this command.

## Q.What is React.createElement?
- It's a method used to create virtual DOM elements which will be rendered on the webpage.

## Q.What are the three properties that createElement accept?
- There are types of properties which accepted by the createElement method -
    1.tagName
    2.Props
    3.Children

## Q.What is the meaning of  root?
- In react it refers to the top most component where all other components get mounted.

- In React, "Render" refers to the process of generating HTML markup from JSX code using






