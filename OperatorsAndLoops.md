# Assignment Operators  

---

An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = f() is an assignment expression that assigns the value of f() to x.  

**Assigning to properties**  
If a variable refers to an object, then the left-hand side of an assignment expression may make assignments to properties of that variable.  

# Comparison Operators  

---

A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values.  
-Equal (==)  
-Not equal (!=)  
-Strict equal (===)  
-Strict not equal (!==)  
-Greater than (>)  
-Greater than or equal (>=)  
-Less than (<)  
-Less than or equal (<=)  

# Loops  

---

Loops offer a quick and easy way to do something repeatedly. You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times.  

**For Statement**  

A for loop repeats until a specified condition evaluates to false. A for statement looks as follows:  

for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement  
  
  When a for loop executes, the following occurs:

1.The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.  

2.The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)  

3.The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.  

4.If present, the update expression incrementExpression is executed.  

5.Control returns to Step 2  

**While Satement**  

A *While Statement* repeats until a specified condition evaluates to true. A *While Statement* looks as follows:  

  while (condition)  
  statement  
  
  If the *condition *becomes false, statement within the loop stops executing and control passes to the statement following the loop.  
  The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.  
  
  For both **For** and **While** Statements. To execute multiple statements, use a block statement ({ ... }) to group those statements.




