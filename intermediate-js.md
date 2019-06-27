# Intermediate Javascript Assessments

### Without using Google answer the following:

1. What is the difference between .map() and .filter()?

They do different things: filter returns a subset of the elements from the original array, map produces an array with new different entries based on the elements in the original array.

2. Why would you use object destructuring?

To unpack values from arrays or properties from objects into distinct variables

3. What is the difference between var, let, and const?

var declarations are globally scoped or function scoped
var variables can be updated and re-declared within its scope
var variables are hoisted to the top of their scope and are initialized with undefined
var can be declared without being initialized

let is block scoped
let variables can be updated but not re-declared
let variables are hoisted to the top of their scope and are not initialized
let can be declared without being initialized

const is block scoped
const variables can not be updated nor re-declared
const variables are hoisted to the top of their scope and are not initialized
const must be initialized during declaration

4. Why is testing important?

It points out defects and errors made during the development phases

5. What is a higher order function?

Its a function that accepts other functions as parameters and/or use a function as the return value.
map(), filter(), reduce() are examples

6. What is the difference between a class and an object?

A class is a blueprint for objects. Classes define objects attributes and behavior.
An object is an instance of a class. An object is a collection of properties and a property is an association between a name(key) and a value.

7. What did you learn during the group project this week? Please include any additional feedback you may have.

Working on React in the group was very helpful.

### HTML/CSS Review questions: First, try to answer each question on your own then Google the answer to further your knowledge.

1. How do you link a CSS file to your HTML page?

You need to insert the <link /> into HTMl document between the <head> </head> tags.
The <link /> has few attributes:
  rel - defines what relationship between the file in which this command is written and the file which is defined in the href path is.
  type - defines the content of the file to which its linked.
  href - specifies the location of the file which you need to create a link with.


2. What is the difference between a div and a span?

Span is in-line element and usually used for a small chunk of HTML inside a line, such as inside a paragraph.
Div is block-line element and used to group larger chunks of code.

3. What is a CSS class? When should you use an id instead of a class?

Classes are reusable styles that can be added to HTML elements. Classes are not unique. You can use the same class on multiple elements. You can use multiple classes on the same element.
ID is not reusable. ID's are unique. Each element can have only one ID. Each page can have only one element with that ID.
Reusable stuff should be kept in a class and unique should be kept in an ID.
Classes have no special abilities in the browser but IDs do.
You need an ID to use getElementById function.

4. Name 4 semantic HTML tags.

<form>
<table>
<header>
<footer>

5. What are three options for creating responsive design?

Flexible layouts - using a flexible to create the website layout that will dynamically resize to any width.
Media queries - an extension to media types when targeting and including styles. Media queries allow designers to specify different styles for specific browser and device circumstances.
Flexible media - makes images, video and other formats scalable by changing the size of the media as the size of the viewport changes.


### Stretch: The following questions are potential interview questions. First, try to answer each question on your own then Google the answer to further your knowledge.

1. What is front end development? Can you identify any tools/skills that are uniquely required of front end developers?

Front-end web development also known as client-side development is how design gets implemented on the web so user can see and interact with it directly.
HTML, CSS, JS

2. What is block scope in JavaScript?

A block is a chunk of code bounded by {}. Anything within curly braces is a block and only available for use within that block.

3. How would you explain the idea of "inheritance" in object oriented programming?

Inheritance is a mechanism in which one class acquires the property of another class.
