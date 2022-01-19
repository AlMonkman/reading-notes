# CSS Layout

---

The display property does two things. The first thing it does is determine if the box it is applied to acts as inline or block.  
Inline elements sit next to eachother in the inline direction. Block elements create a whole new line for themselves and expand to the size of the inline dimension.  

## Layout Mechanisms  
- **Flexbox** is a layout mechanism for one-dimensional layouts. It will layout across a single axis. Items will stay on the same axis and not wrap when they run out of space.  
- **Grid** is very similar to the *Flexbox* layout, but is designed to control multi-axis layouts. 
- **Flow** is the way your elements will display if you are not using *grid* or *flexbox*.  

- Using **inline-block** will give you a box that has some of the same characteristics as a block-level element, but still flows inline with the text.  
- The **Float** property instructs an element to float in the direction specified. You can instruct an element to float left, right or inherit. 

- If you have a very long list of elements, you can use the **multicolumn** layout to split it into multiple collumns. This decreases scrolling time and gets rid of unnecessary white space.  

- The **position** property changes how an element behaves in the normal flow of the document, and how it relates to other elements. The available options are *relative*, *absolute*, *fixed*, and *sticky*. The default is *static*.   
