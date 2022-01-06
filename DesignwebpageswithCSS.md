# CSS  

---

**What is CSS?**  

Browsers will style HTML using an internal stylesheet, headings will be larger, links will be underlined and highlighted, listed items get a bullet or number. Etc. However this would all be the same for every website if not for CSS. CSS is a way to personalize your content and present your markup using whatever design you like.  

CSS can be used for all sorts of different things on your webpage.  
-Text  
-Border  
-Margin  
-Background  
And many more.
These are all called properties. And you can give an assigned *Value* to each one of those properties if you so desire.  

**Here is some basic CSS format**  

h1 {  
    color: red;  
    font-size: 5em;  
}  

The h1 is knows as the selector. This selects which HTML element that we are going to style.  

The color and font size are the properties, and "red" or "5em" are the values we are giving those properties. Seperate the property and the value with a colon. The pair of property and value is known as a declaration, each must be closed with a semi colon.   

The declarations must be wrapped inside a set of curly braces with the selector right in front of them. 

# How to add CSS  

---

There are 3 ways to insert CSS.  

1.External  
2.Internal  
3.Inline  

**External**  

With a seperate (external) stylesheet you can add all the CSS you want, without it cluttering up the code you have in another file. You simply need to add a link to your CSS stylesheet.  

Place this link in the head of your HTMl document. The name of your particular stylesheet will go where it says "mystyle.css"

`<link rel="stylesheet" href="mystyle.css">`


**Internal**  

You can also internally add the style that you would like by simply using a <style></style> element inside the head of your document. This is especially usefull if you have one page on your website that has it's own unique style.  

**Inline**  

An inline style brings it down even further and can be used for just a single element you want to look a particular way. You simply add it to the element like so.  

`<h1 style="color:blue;text-align:center;">This is a heading</h1>`  

If you have multiple styles affecting the same element certain styles will take priority.  
-Inline will have the highest priority  
-Followed by external and internal style sheets  
-And finally the browsers default  

# Colors  

---

There are several different ways to add color to your site. You can simply type color as the property in your declaration. From there you can choose from a long list of available colors that CSS has to offer. Alternatively there are several different things you can do to pick a color.  
 
 You may set your color with a...  
 -RGB Value  {color: rgb(0,0,0);}  
 -Hex Value {color: 92a8d1;}  
 -RGBA Value {color: rgba(0,0,0,0);}  
 -HSL Value {color: hsl(89,20%,60%);}  
 -HSLA Value {color: hsla(89, 43%, 51%, 0.6);}  
 
 Choose which ever way suits you the best as a developer.
