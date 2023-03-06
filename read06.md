# Read 06 Notes

## How would you describe an object to a non-technical friend you grew up with?
* In programming, an object is a container that holds related information and functions. Think of it like a box that has a label on it - the label tells you what's inside the box, and the box itself holds a bunch of related things. So, an object in programming works kind of like that - it's a container that holds a bunch of related information and functions, and we can use it to organize and work with data in our programs.

## What are some advantages to creating object literals?
### There are several advantages to creating object literals in programming. Some of the main benefits include:

* Objects are a flexible way to store and organize data, making it easy to work with and manipulate information in your programs.
* Objects can contain complex data structures and functions, which can help to simplify your code and make it easier to read and understand.
* Objects are a fundamental concept in many programming languages, so learning how to work with them can help you to develop strong programming skills that are transferable across a wide range of languages and technologies.

## How do objects differ from arrays?
* While both objects and arrays are used to store and organize data in programming, there are some key differences between them. Objects are collections of key-value pairs, where each key is a unique identifier for a value. Arrays, on the other hand, are ordered collections of values that can be accessed using numeric indices. Another difference is that objects can contain functions, while arrays cannot.

## Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
* In JavaScript, you can access the properties of an object using either dot notation or bracket notation. Generally, dot notation is preferred because it's easier to read and write. However, there are some cases where you might need to use bracket notation instead - for example, when the property name is stored in a variable or contains special characters.

let myObj = {
  "property with spaces": 42
};

// Using dot notation won't work here, because the property name contains spaces:
console.log(myObj.property with spaces); // Uncaught SyntaxError

// Instead, we need to use bracket notation and enclose the property name in quotes:
console.log(myObj["property with spaces"]); // 42

## What is the DOM?
* The Document Object Model, or DOM for short, is a programming interface for HTML and XML documents. It represents the page so that programs can change the document structure, style, and content. The DOM is essentially a tree-like structure that represents the hierarchy of elements on a web page, with each element represented by a node in the tree. Developers can use the DOM API to programmatically interact with the elements on a web page, such as reading or modifying their properties, and adding or removing elements dynamically.

## Briefly describe the relationship between the DOM and JavaScript.
* JavaScript is a programming language that can interact with the DOM API, allowing developers to manipulate the content and structure of a web page in real time. When a web page is loaded, the browser creates a representation of the page as a DOM tree. JavaScript can then be used to modify this DOM tree, by adding or removing elements, changing their attributes or contents, and responding to user events such as clicks or scrolls.
In this way, JavaScript and the DOM work together to create dynamic and interactive web pages. JavaScript provides the logic and interactivity, while the DOM provides the structure and content of the page. Developers can use JavaScript to interact with the DOM API to create rich and engaging web applications.
