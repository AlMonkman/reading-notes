# Reading 01: Introductory HTML and Javascript  

---

## HTML  

**Structure**  

-Tags are often refered to as Elements  

-Tags act like containers. They tell you something about the information that lies between their opening and closing tags.  

-Attributes provide additional information about the contents of an element. They appear in the opening tag of an element and are made up of two parts: a name and a value.  

-The attribute name indicates what kind of additonal information you are supplying about the elements content. It should be written in lowercase.  

-The value is the information or setting for the attribute. It should be placed in double quotes. Different attributes have different values.  

-The majority of attributes can only be used on certain elements, although a few can appear on any element.  

-One of the best ways to improve your web design skill is to look at other people websites. To do this go to the website and view the source code in the browser(right click on pc and hit inspect).  

**Extra Markup**  

-Since the Web was first created there have been several different versions of HTML. Because there have been several versions, each webpage should begin with a !Doctype tag indicating which version you are using.  

-If you want to add a comment to your code that will not be visable in the user's browser, you can add the text between these characters. \<!-- Comment goes here -->. It is a good idea to add comments as it makes it much easier for other developers to understand.  

-Each HTMl element can carry both an "Id" attribute and a "Class" attribute.  

-The "Id" is used to identify that element from other elements.

-The "Class" is a way to identify a group of elements from others.  

-Block elements will always appear to start on a new line in the browser window. Example: \<h1>,\<p>,\<ul>,\<li>
  
-Inline elements are the opposite. They will appear to continue on the same line. Example: \<a>,\<b>,\<em>,\<img>  

-The \<div> element allows you to group a set of elements together in one block level box.  

-The \<span> element is the inline equivalent of the \<div>.  

-An \<iframe> is like a little window that has been cut into your page, in said window you can see another page. A common use of this is a google map page.  

-The \<meta> element lives inside the \<head> of your page and contains information about your page that is not visable to users.  

-Escape characters are used to include special characters in your code without interfering with the HTML itself.  

**HTML5**  

-HTML5 is the updated version of HTML that we use today.  

-The new elements provide clearer code.  

-Older browsers need to be told which elements are block level elements.  

-Extra JavaScript is needed to make HTML5 work on internet explorer 8 or older versions.  

**Process and Design**  

-There are key things you need to think about before you sit down and start creating your new site.  
- Who is the site for?  
- Why people will visit your website.  
- What your visitors are trying to achieve.  
- What information your visitors need.  
- How often people will visit your site.  

-Now that you know what needs to appear on your site you can use a "site map" in order to organize the information into sections or pages.  

-Create a "Wireframe" for each seperate page to decide how they will individually look.  

-Most web users do not read entire pages. Use contrast to create a "visual heirarchy" that makes it easier for the user to find what they are looking for.  

-Group things together by similarity.  

## Javascript  

---

-You can use JavaScript to select any element, attribute, or text from an HTML page.  

-You can then modify what you have selected using JavaScript.  

-You can specify a set of steps for the browser to follow (like a recipe).  

-You can also use JavaScript to react to events. Allowing to user to interact more with your Site.  

**The ABC's of Programming**  

-A "Script" is a series of instructions that the computer can follow to achieve your desired goal.  

-Often scripts will need to perform different taks in different situations. Flowcharts will help you set this up by showing the path between each step.  

-Computers use data to create models of things in the real world. Events can trigger methods, and methods can retrieve or update an objects properties.  

-HTML, CSS, And JavaScript are the three basic components of every web page. When possible aim to keep the three languages all in seperate files.  

-Connect your files together using a script element for JavaScript. The src attribute tells the code where the JavaScript file is stored. This is similar to using the link element for a CSS file.  

-Where you place it in your HTML code is where the browser will load it in.  
