# HTML Lists, Control Flow with JS, And the CSS Box Model  

---  

## HTML Lists

**Ordered lists**  
A list where each item in the list is numbered.  
It is created with the `<ol>` list tag.  
Each item in the list is placed between an opening `<li>` tag and a closing one.  

**Unordered lists**  
A list where each item in the list begins with bullet point.  
It is created with the `<ul>` tag.
It also uses the `<li>` tags.  

**Definition lists**  
A list that is made up of a set of terms along with the definitions for each of those terms.  
It is created with the `<dl>` tag.  
The `<dt>` tag is used to contain the term being defined.  
The `<dd>` tag is used to contain the definition.  

**Nested lists**  
You can put a second list inside an `<li>` element to create a nested list.  

## CSS Boxes  

- By default a box is sized just big enough to hold its contents. Use the *width* and *height* properties to control the size of the box.  
- Use the *min-width* and *max-width* properties or the *min-height* and *max-height* properties to ensure contents of your page are lefible for all different screen sizes.  
- The *overflow* property tells the browser what to do if the content contained within the box is larger than the box itself. *Hidden* will hide any of the excess. *Scroll* will add a scrollbar.  
- Every box has three available properties that can be adjusted to control its appearance.  
1. Border(The outer edge of the box).  
2. Margin(The space between the outside of your box and other content on the page).  
3. Padding(The space between the inside of your box and the content inside.  
- It is possible to hide elements using the *dispay* and *visibility* properties.  
- You can change Block-level boxes into in-line and vice versa.  

## Switch Statements  

- A switch statement starts with a variable called the *switch value*. Each case indicates a possible value for this variable and the code that should run if the variable matches said value.  
- Every value in JavaScript will be treated as true or false(truthy or falsey).  
- Logical operators are processed left to right. They stop(short circuit) as soon as they have a result. Experienced programmers often put the code most likely to return true first in OR operations. And false answers first in AND operations.  

## Loops  

 Loops check a condition. If it returns true then a code block will run. This repeats until the condition returns false.  
 
 - **For loops** are for when you need to run code a specific number of times.  
 - **While loops** are for if you do not know how many times your code will need to run.  
 - **Do while loops** are very similar to the *while loop*, but there is one key difference. It will always run the statements inside the curly brackets at least once, even if the condition evaluates to false.  

