# Expressions and operators
## operators 
1. JavaScript has both binary and unary operators.  
   1. binary operator requires two operands `3+4`  
    2. unary operator requires a single operand ` x++`
2.  Assignment operators `x = y` , compound assignment operators `x += y` resulting sum `x + y` 
3. When chaining expressions, each assignment is evaluated right-to-left.  
4. Destructuring means  `var [one, two, three] = foo;` ` var one   = foo[0];
var two   = foo[1];
var three = foo[2]`
5. Comparison operators  **returns a logical value** `Equal (==)` returns true or false
6. Arithmetic operators : (+, -, *, /)
7. Logical operators : Logical AND (&&) , ogical OR (||) ,Logical NOT (!)
8. String operators `console.log('my ' + 'string')`; // console logs the string "my string".

# Loops and iteration
* repeat an action some number of times
## for statement 
A for loop repeats until a specified condition evaluates to false. 
> for ([initialExpression]; [conditionExpression]; [incrementExpression])
statements        

```  
  for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}
```   


## while statement 
* A while statement executes its statements as long as a specified condition evaluates to true
> while (condition)  
  statement   
* The condition test occurs before statement in the loop is executed.  
```   
let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}
```   

