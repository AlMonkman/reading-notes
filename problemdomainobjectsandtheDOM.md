# Problem Domain, Objects, and the DOM.  

---

## Problem Domain
Understanding the problem domain can be one of the hardest aspects of coding. It can be very difficult to understand and look completely different depending on your viewpoint. If you want to make udnerstanding the domain easier there are some things you can do.  
- Make the domain problem easier by cutting out cases and only focusing on particular parts of the problem at a time. 
- Get better at understanding the problem domain by sitting down and talking to the customers or business people who know more about your problem domain.  

## Primitive values and Object references

There are 8 different data types in JavaScript  
- Boolean
- Null
- Undefined
- Number
- BigInt
- String
- Symbol
- Objects  

Primitive values and object references are stored in JavaScript programs in different ways. When a primitive value is assigned to a variable the variable is set to that value directley.   
When a primitive value is assigned with an object, instead of containing the value directly, that variable contains a reference to it that is stored in the computer memory.  

Primitive values cannot be changed whereas object references are subject to change.  

## Object Literals

Objects group together a set of variables and functions to create a model of something. In an object, variables and functions take on new names.  
Literal notation is the easiest way to create objects. 

The object is the content of what is inside your curly braces and it is stored inside a variable of your choosing.

You access the properties or methods of an object using dot notation. You can also access properties using square brackets. 

object.property;  
or  
object[property];

## DOM Documenting Object Model  

- DOM specifies how browsers should create a model of an HTML page and how JS can access and update the contents of a web page while its in the browser window.  
- DOM trees have four types of nodes. Document nodes, Element nodes, Attribute nodes, and text nodes.  
- You can select element nodes by their id or class attributes, by tag name, or using CSS selector syntax.  
- When you access any element, attribute or text node you navigate to it via the document node.  
- Methods that find elements in the DOM tree are called DOM queries. If you need to work with an element more than once, you should use a variable to store the results of this query. 
- getElementById() and querySelector() can both search an entire document and return individual elements.  
- There are two ways to select an element from a NodeList. The item() method and array syntax. Both require the index number of the element you want.  
- There are also two different approaches to adding and removing content from a DOM tree: innerHTML property and DOM manipulation.  
- DOM manipulation is better suited fo individual nodes, whereas innerHTML is better suited to updating entire fragments.  
- 


