# Chart.js, Canvas  
---  

## Chart.js  

Charts are far better at displaying data visually than basic tables. There are three basic chart displays that can be used with the chart.js code.  
- Pie charts  
- Line charts  
- Bar charts  

First you need to add your canvas element into your HTML to render your chart. Next add the script tag and customize your chart based on the data you want to display.  

## Canvas  

A canvas element looks like an img element except for a few key differences. Insted of a src and alt The canvas has the height and width inside of the tag itself.  

It is always a good idea to give your element either an id or a class tag. Making it much easier to target in with either CSS or JavaScript.  

You want to always assign fallback content to your canvas tag, as older browsers do not always support canvas.  

Because of how the fallback content is provided the canvas tag always needs the closing tag(`</canvas>`).  

**Drawing Shapes/Color**  

- Normally one unit on the grid corresponds to one pixel on the canvas.  
- The origin of this grid is positioned in the top left corner at coordinate (0,0).  
- All elements are placed relative to it's origin.  
- You can draw different shapes using their corresponding functions/methods. 
- In order to customize the shapes you have drawn, you will need to simply use some simple properties and decide what colors you want your shapes to be filled in with.  
- You can also target and change the transparacy of the shapes.  
- You can also target the lines themselves and completely customize how they look, width, their junction sizes and more.  

**Filling in text**  

Drawing text on your canvas is very similar to the drawing we were doing above, but it has its own set of methods to use.  

You use many of the properties that we are already familiar with to stylize the font style, width, color and other properties of text.  
