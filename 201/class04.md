# Class 04 Summary

## HTML Links

[Links](https://www.w3schools.com/tags/tag_a.asp)

When it comes to creating links, its important to note that hyperlinks can indicate the link's description. In HTML, developers use the **a** tag for linking a page with the href attribute & the href specifies the URL of the page in which the link goes to.

![directory structure](https://stuyhsdesign.files.wordpress.com/2015/09/directory-structure1.png)

When it comes to dealing files, its crucial to notice the fact the developer can assemble files into a structure which gathers all the contents together & also making sure that the materials remain in the folders with the webpage files. The structure that the website must have is not only based on linking materials & URLs in the HTML, but also the HTML file along with the CSS, JS files & images must be combined together. For file paths & image linking, it is similar to linking websites except the fact that it uses the **img** tag instead of the **a** tag. The **img** tag contains an **src** attribute which locates the path of the image file as well as the image link.




![Email link](https://www.wikihow.com/images/thumb/5/55/Create-an-Email-Link-in-HTML-Step-7.jpg/aid1794734-v4-728px-Create-an-Email-Link-in-HTML-Step-7.jpg)

Its very important to notice nowadays that every single website has a contact page, but most importantly has links for contact such as social media pages, phone numbers & most importantly emails. In HTML, the emails are written the same way as the normal links, but the href attribute is instead **mailto: email**.

[target attribute](https://www.w3schools.com/tags/att_a_target.asp)

When it comes to opening new tabs, the HTML linking tag consists of a target attribute. The target attribute specifies the location of the website that needs to be opened.

## HTML layouts

![position](https://cdn.educba.com/academy/wp-content/uploads/2019/12/CSS-Position.jpg)

When it comes to positioning the elements of the HTML, the CSS specifies the type of positioning the elements & it consists of positioning values such as:

 * Static - It doesn't affect by any property of the element & it is always positioned based on the normal flow of the page.
 
 * Relative - It is related to the normal position, but it can be adjusted from the normal position in which the elements can be moved with it

 * Fixed - It always stays in the same place even if the page is scrolled because the HTML properties position the elements in which doesn't leave a gap in the page.

 * Absolute - This one is postioned to the nearest parent or ancestor element because if the absolute position is not placed next to its parent or ancestor element, it will use the document body & moves with the page scrolling.

 * Sticky - This one is based on the element being stuck on the page even when the user is srolling the page because it toggles between the relative & fixed positions which depends on the scrolling position.

 [clear property](https://css-tricks.com/almanac/properties/c/clear/)

 The clear property allows the user to implement the elements that can fit horizontally or vertically next to elements that are floated. However, the clear property allows the developer to place the next to each other either on the left, right, both or none.

![screen](https://i0.wp.com/css-tricks.com/wp-content/uploads/2015/02/cover-and-contain.jpg?ssl=1)

 Depending on the developer's choice, its simple to note that the website is developed according to the size of the monitor but also resizing certain elements. Most web developers create websites which measures from 960 pixels to 1000 pixels so that user can see the design of the website in their computer screens.

 [fixed & liquid layouts](https://tutorial.techaltum.com/css_fixed_liquid_layout.html)

 The similarities between the fixed & liquid layouts is the fact that sometimes the fixed page doesn't change its size when the developer increases or decreases it. However, the liquid layouts can be resized by the developer by using percentages.

 [grids](https://css-tricks.com/snippets/css/complete-guide)

 Grids are based on arrangements of visual elements which are organized in the website in which the developers can implement art structures such as photos, paintings & vice versa.

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
