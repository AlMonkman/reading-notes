# Passing Functions as Props
---

## Lists and Keys

**1. What does .map() return?**  
 .map() will always return an array.  

**2. If I want to loop through an array and display each value in JSX, how do I do that in React?**  
 Using the `.map()` function you would need to return an *li* element for each item in your array and assign them to a variable. You then need to include said variable inside of a `<ul>` element.  
 
**3. Each list item needs a unique ____.**  
Each list item needs a unique *key*  

**4. What is the purpose of a key?**  
The purpose of a key is to help React identify which items have been added, changed, or removed. As a last resort you can use the item index to identify a list item, however, this is not reccomended as the order of your items may change.  

## The Spread Operator  

**1. What is the spread operator?**  
The spread operator expands an iterable object into a list of seperate arguments.  

**2. List 4 things that the spread operator can do.**  
- Copy an array
- Combine array's  
- Use Math functions  
- Use an array as an argument  
- Add an item to a list  
- Add to state in React  
- Combine objects  
- Convert NodeList to an array  

**3. Give an example of using the spread operator to combine two arrays.**  
Array concatenation:  

Const arrayOne = [];  
Const arrayTwo = [];  
Const arrayOnePlusTwo = [...arrayOne,...arrayTwo];    

**4. Give an example of using the spread operator to add a new item to an array.**  

Const numArray = [4, 5, 6];  
Const moreNumArray = [1, 2, 3, ...numArray];  
Console.log(moreNumArray) // Array(6) [1, 2, 3, 4, 5, 6]  

**5. Give an example of using the spread operator to combine two objects into one.**  

Const objectOne = {name: 'Frank'};  
Const objectTwo = {location: 'Seattle'};  
Const objectThree = {...objectOne, ...objectTwo, hairColor: Brown};  
Console.log(objectThree) // Object {name: 'Frank', location: 'Seattle', hairColor: Brown};  

## How to Pass Functions Between Components  

**1. In the video, what is the first step that the developer does to pass functions between components?**  
You need to create the function whereever the state is that you want to change.  

**2. In your own words, what does the increment function do?**  
The increment function is looping through his array with .map(), and returning a new array with the *count value* updated if that name was selected.  

**3. How can you pass a method from a parent component into a child component?**  
You can pass the method the same way you would as any other prop.  

**4. How does the child component invoke a method that was passed to it from a parent component?**  
You then need to call said method inside of the child component and pass in a *name*.  


## Things I want to know more about  
- I am curious to see how often I will be using the spread operator. It seems incredibley useful.
