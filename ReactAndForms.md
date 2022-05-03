# React and Forms  
---

## Forms  

**1. What is a ‘Controlled Component’?**  
A controlled component is a component that handles the submission of a form and also has access to the data that the user entered in the form.  

**2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why**   
The displayed value will update as the user types because the React state is the "single source of truth".

**3. How do we target what the user is entering if we have an event handler on an input field?**  
{this.state.value}  

## Ternary Operator  

**1. Why would we use a ternary operator?**  
If we use a ternary operator on a regular if statement we can change it into just one line of code.  

**2. Rewrite the following statement using a ternary statement:**  

**if(x===y){  
  console.log(true);  
} else {  
  console.log(false);  
}**  


x===y ? console.log(true) : console.log(false)
