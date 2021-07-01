# Read07 summary

# Javascript functions
![Javascript functions](https://i.redd.it/1x4ho2qngv421.jpg)

The functions is based on a block of codes that does tasks in which these codes can be reused & organized. The function consists of methods that can be defined, expressed & called.

### Function declaration

Function declaration or definition is based on displaying the function's name & parameters which defines the function with a return value.

For example:

function name(1+2)

{
  return name;
}

### Function expression

The expression method works in a function by storing variables in it. The function defines the variables inside an expression.

For example:

var sum = function(1+2)

{

  return sum;

}

In the example above is the expression in which the user inserts a variable which equals to the task that needs to return the sum value.

### Operators in functions

In the last [summary](https://nedal1994.github.io/reading-notes/read05), I  explained about the types of operators. However, those operators can be used in the functions in which the user feels satisfied with but at the same time, it mainly helps with the return statements in a way that it is functions properly.

For functions it is important to note that as a programmer it is mandatory to implement prompt & alert boxes to make sure that those operators work in a function in which the user inserts certain numbers or variables that can do any kind of operations that returns a certain value such as arithmetic, assignment, logical, comparison, conditional, etc...

Here are examples below:
* function sum()

{

var result = 4+5;
return result;

}

* var num1 = prompt("Insert the first number");

var num2 = prompt("Insert the second number");

function sum(n1,n2)

{

  console.log('n1' ,n1);

  console.log('n2' ,n2);

  var result=parseInt(n1) + parseInt(n2);

  return result;

}
console.log(sum(num1,num2));
