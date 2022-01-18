# HTML Tables, JavaScript Constructor Functions  

---

## HTML Tables

A table represents information in a grid format.  
Grids allow us to understand complex data by referencing information on two axes.  
Each block in the grid is referred to as a **table cell**.

- The `<table>` element is used to create your table. The contents of the table are written out row by row.  
- You indicate the start of each row using the `<tr>` element (table row).  
- Each cell of a table is represented using the `<td>` element (table data).  
- The `<th>` element (table heading) is used just like the `<td>` element but its purpose is to represent the heading for either the collumn or row.  
- If you need your table entry to stretch across more than one collumn you use the *colspan* attribute.  
- If you need your entry to stretch down across more than one row you would use the *rowspan* attribute.  
- For long tables, you can also help distinguish between the main content of your heading, and the first and last row, using these three elements. `<thead>`, `<tbody`>, `<tfoot>`.  

## Domain Modeling  

Domain modeling is the process of creating a conceptual model in code for a specific problem.  
An entity that stores data in *properties* and encapsulates behaviors in *methods* is referred to as an *object-oriented* model.  
These models can be used as a communication tool that both business teams and technical teams will understand.  

- To define the same properties between many objects, you'll want to use a constructor function. It is defined using a *function expression*.  
- To model the random nature of user behavior, you'll need the help of a random number generator. You can use the JS Math.random() Function for these occasions.  


## Objects  

- The *new* keyword and the object constructor create a blank object that you can then add properties and methods to.  
- To update the value of properties you use the dot notation or square brackets.  
- To delete a property, use the *delete* keyword.  
- Sometimes you will want to use several objects to represent similar things. Object constructors can use a function as a template for creating objects. You first need to create the template with the objects properties and methods.  
- The keyword **This** is used to alter what *this* means. It always refers to one object and is usually the object in which the function operates.  
- *Array's* are a special type of object. They hold a related set of key/value pairs, but the key for each value is its index.  
- You can combine arrays and objects to create complex data structures. Arrays can store a series of objects, and objects can also hold arrays.  

There are 3 different types of *Built-in* objects.  

- Browser object model  
- Document object model  
- Global Javascript objects  

To create a *date* object you need to use the date() object constructor. By default it will hold today's current date and time, this can be changed.  
