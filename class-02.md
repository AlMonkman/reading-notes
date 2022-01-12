# Reading:02-Basics of HTML, CSS & JS  

---

## Text  
**Structural Markup**  

The elements you can use to describe both headings and paragraphs.  

- Headings `<h1>`, `<h2>`, and so on.  
- Paragraphs `<p>`
- Bold `<b>`
- Italic `<i>`
- Superscript `<sup>`
- Subscript `<sub>`  
- Line breaks `<br />`
- Horizontal Rules `<hr />`

**Semantic Markup**  

Provides extra information; such as where emphasis is placed in a sentence, shows what is quoted and who said it, the meaning of acronyms, and so on.  

- Strong `<strong>`
- Emphasis `<em>`
- Long quotes `<blockquote>`
- Shorter quotes `<q>`
- Abbreviations & Acronyms `<abbr>`
- Citations `<cite>`
- Definition `<dfn>`
- Author details `<address>`
- Content inserted `<ins>`
- Content deleted `<del>`
- No longer accurate `<s>`  

## Introducing CSS  

Imagine there is a box around every HTML element. CSS allows you to create rules that control the way that each box and it's contents is presented.  
A CSS rule contains two parts. A selector and a declaration.  
The selector targets which HTML element you will be modifying.  
Declarations sit inside curly brackets and each is made up of two parts. A property and a value, seperated by a colon. You can specify several properties in one declaration, each seperated by a semi-colon.  
You can use *external CSS* by using the `<link>` element to tell the browser where to find your seperate CSS file.  
Or you can use *internal CSS* by using a `<style>` element inside of you head element on the page.  


## Basic JavaScript and Instructions  

**Language**  
- A script is a series of instructions that a computer can follow one-by-one. Each individual instruction is known as a *statement*.  
- You should always write *comments* to explain what your code does. This will help others who read your code.  
- Your script will temporarily need to store bits of information it needs to do it's job. It will store this data in *Variables*.  
- To declare a variable you need to declare it. There are many ways to do this, but the most common up-to-date way is using the *let* command.  
- Use the = (assignment operator) to assign a value to your variable.  
- JavaScript distinguishes between numbers, strings, and true or false statements known as booleans.  

Here are 6 rules you must always follow when giving a variable a name.  

- The name must begin with a letter, $, Or an _. It must not start with a number.  
- The name can contain letters, numbers, $, Or an _. You cannot use a - or . in a variable name.  
- You cannot use *keywords* or *reservered words*.  
- All variables are case sensitive.  
- Use a name that describes the kind of information the variable stores.  
- If your variable is made up of more than one word, use a capital letter for the first letter of every word **after** the first word.  


An array is a special type of variable that stores a list of values as opposed to just one. *Expressions* evaluate into a single value, they rely on *operators* to calculate the value.  


## Decisions and Loops  

**Evaluations**  
You can analyze values in your script to determine whether or not they match expected results.  

**Decisions**  
Using the results of evaluations, you can decide which path your script should go down.  
There are two components to a decision:  
- An expression is evaluated, which returns a value.  
- A conditional statement says what to do in a given situation.  

**Loops**  
There are also many occasions where you will want to perform the same set of steps repeatedly.  

**Comparison Operators**  
- == (is equal to)
- != (is not equal to)
- === (strict equal to)  
- !== (strict not equal to)  
- `>` (greater than)  
- < (less than)  
- `>=` (greater than or equal to)  
- <= (less than or equal to)

**Logical Operators**  
- ** (logical and)
- || (logical or)  
- ! (logical not)

**If Statements**  
The if statement evaluates a condition. If the condition evaluates to true, the following code block is executed.

**If...Else Statements**  
The if...else statement checks a condition. If it resolves to true the first code block is executed.
If false the second code block is run instead.  






