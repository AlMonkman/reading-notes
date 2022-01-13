# HTML Links, JS Functions, and CSS Layout.

---

## HTML Links


- Links allow you to move from one website to another. They are created using the `<a>` element.  
- You specify which page you want to link to using the "href" attribute. And the text between your opening and closing tags is what the user will see and click on to move pages.  
- The element looks like this. `<a href="link"></a>`  
- When linking withing the same site, you do not need to specify the domain name.  
- To create a link that starts up the users email and sends an email. The value of the "href" starts with mailto: and is followed by the email address you are sending too.  
- To open a link in a new window, simply add a "target" attribute in the opening `<a>` tag. The value of the attribute should be _blank.  
- To link to certain spots on the same page you need go give `<id>` tags to the points on the page you are linking to. The value of the "href" attribute will start with a # and then is followed by the value of your desired `<id>` attribute.  
- To link to a specific part of a different page, the "href" attribute will have the url to said page. Followed by the # and that "id".  

## Layout With CSS  

CSS treats each element as if it is in it's own box. This box will either be a block-level box or an inline box.  

- **Block-Level Elements** These are the main building blocks of any layout. Examples include `<h1>`, `<p>`, `<ul>`, `<li>`.
- **Inline Elements** These flow between surrounding text. Examples include `<img>`, `<b>`, `<i>`.

If one "block-level" element sits inside of another. Then the outer box is called the containing or parent element.

CSS has the following "positioning schemes" that allow you to control the layout of a page. To specify you need to use the position property in CSS.  
- Normal Flow  
- Relative Positioning  
- Absolute Positioning  
- Fixed Positioning  

You can also use the float element to position things where you want. (Floated items require a defined width).    

Screen size and resolution are all different when it comes to your user's. There are different layouts you can use depending on what you are trying to create.  
- **Fixed Width Layout** These do not change size as the user increases or decreases their window. Measurements tend to be given in pixels.  
- **Liquid Layouts** These stretch and contract as the user changes their window. They tend to use percentages.  

## Functions  

Functions let you group a section of your code together that perform a specific task. You can later "call" the function instead of writing out all that code again.   

To create a function you first need to declare it. Use the function keyword, followed by the name you want the function to have followed by parenthesis. The statements that perform your task sit after that inside of curly brackets. It looks like this.  
function identifier() {task}

Now that your function is declared, you can call it later by simply writing the functions name (identifier) followed by parenthesis. identifier();  

Sometimes a function needs specific information to perform it's task. In such cases, when you declare the function you give it parameters. Inside the function, the parameters act like variables.  
Example:   
function getArea(width, height) {  
return width * height;  
}

To call this function you simply name the function and in parenthesis you place the values you want it to use. These values are called arguments.  

