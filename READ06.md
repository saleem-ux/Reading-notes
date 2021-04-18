## WAHT IS A FUNCTION?
Functions let you group a series of statements together to perform a 
specific task. If different parts of a script repeat the same task, you can 
reuse the function (rather than repeating the same set of statements).

## DECLARING A FUNCTION
A function is a group of statements that, together, perform a task.
A function declaration tells the JavaScript engine about a function’s name, return type, and parameters. When a function has been declared, it can be used anytime inside a class or development scope whenever it’s been called/invoked.
To declare a function, it must start with function name(), just like a variable declaration must start with Var.

![DECLARING](https://miro.medium.com/max/2400/1*YsbsQCj7twkS5Kn8iE0qEw.png)

## ANONYMOUS FUNCTIONS & FUNCTION EXPRESSIONS
A JavaScript function can also be defined using an expression.
Just as we know in JavaScript, an expression is a section of a statement that evaluates a value.
After a function expression has been stored in a variable (Var, let, const), the variable can be used as a function.
Functions stored in variables do not need function names. They are always invoked (called) using the variable name.
![EXPRESSIONS](https://miro.medium.com/max/654/1*suIOV93EyHolabBRpEXVIg.png)  

## Function Declaration vs. Function Expression
![DECLARINGVSEXPRESSION](https://miro.medium.com/max/2400/1*yanrJGQt1AfSOFXSUleBDw.png)
They’re actually really similar. How you call them is exactly the same. The difference lies in how the browser loads them into the execution context.
-	Declaration: Function declarations load before any code is executed.
-	Expression: Function expressions load only when the interpreter reaches that line of code.
-	Declaration: Similar to the var statement, function declarations are hoisted to the top of other code.
-	Expression: Function expressions aren’t hoisted, which allows them to retain a copy of the local variables from the scope where they were defined.
