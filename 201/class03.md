# Class03 summary

## Lists

![lists](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/07/html-lists-df.jpg)

HTML provides a set of lists which allows the developer to implement items in lists. There are 4 types of lists:
  1. Ordered list
  2. Unordered list
  3. Description list
  4. Nested list

![ordered list](https://www.dummies.com/wp-content/uploads/412155.image0.jpg)

The ordered list is based on items are listed in numbers. The ordered list always starts with the **ol** tags then each listed items starts with the tag **li**.

![unordered list](https://media.geeksforgeeks.org/wp-content/uploads/Screen-Shot-2017-11-22-at-1.27.33-AM.png)

Most developers use unordered lists because it allows them to create certain navigation bars, tables & vice versa. It works the same as the ordered list, but the difference is the fact that the items are listed in bullet points or symbols.

![description list](https://cdn.educba.com/academy/wp-content/uploads/2019/12/html-descrition-list-op-3.png)

The description or definition list is based on listing items that consists of details & terms. Unlike the ordered & unordered lists, the description lists consists of 3 tags:
 * d1 - It consists of a set of terms & definitions
 * dt - It is used to contain the defined term
 * dd - It contains the definition

The description list literally works like a dictionary in which the user can implement items with their definition or description which has terms the describes & defines the information of the list.

![nested list](https://s3.amazonaws.com/webucator-how-tos/419.png)

The nested list is a list within a list. It works the exact same method as the unordered list unless if there's a sublist written in it.

[CSS boxes](https://www.w3schools.com/css/css_boxmodel.asp)

In CSS, boxes are based on wrapping the entire HTML elements which consists of margins, borders, padding & content. For sizing, the developer can resize the box dimensions by simply changing the width & height of it.

![boxes](https://miro.medium.com/max/565/1*6DrszcyPybYDGziiS9CWdg.png)

The developer can resize the box by implementing & adjusting the width & height through shrinking & expanding the boxes.

![overflow](https://res.cloudinary.com/practicaldev/image/fetch/s--A_Jl_XX8--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://cl.ly/3P2H2C0b0V1F/Image%25202018-05-07%2520at%25204.47.33%2520PM.png)

When it comes to overflowing , it tells the browser what to do if the content is contained in a box. Overflowing the box consists of either being hidden, visible or scrolled. The hidden property is based on hiding the extra content which doesn't fit in the box while the visibility of the box shows the extra content which expands the content even further than the box. As for the scrolling property, it adds a scrollbar to the box so that users can scroll up & down to see the missing content.

![border](https://i.pinimg.com/originals/41/0b/30/410b30a354bfffe828c542fc120dccfc.png)

Borders are based on boxes around texts which can be specified by its style, size & color of it. Borders are actually lined boxes which can be specfied depending on the developer's satisfaction. Borders are styled in many different designs such as dotted lines, dashed lines, solid lines & so on.

![margins](https://www.freecodecamp.org/news/content/images/size/w1000/2020/01/Artboard-1.jpg)

Margins are properties that create space around the elements outside the borders. The developer can set the width of it by creating a gap between the borders.

![padding](https://cdn.educba.com/academy/wp-content/uploads/2020/02/CSS-Padding.jpg)

Padding is a property that allows the developer to specify the amount of space around the content only this time its inside the border.

![display](https://i1.wp.com/www.tutorialbrain.com/wp-content/uploads/2019/06/CSS-Display.png?fit=474%2C379&ssl=1)

Depending on the developer's choice for displaying the content, the display property specifies the displaying behavior of the element. There are 4 methods that the content can be displayed:
* None - It hides the element from the page.

* Inline - It causes a block level element to take as much width as necessary

* Block - It breaks the flow of the text & starts a new line.

* Inline-block - They are similar to the inline properties, but it continues with the flow of the text & it doesn't break into a new line.

## Javascript

![arrays](https://miro.medium.com/max/1130/1*wc0QOYZUVvabyZYVfdzvTQ.png)

Arrays are variables which holds more than one value which are listed in a way that they are related to each other. They are very useful because it specifies the list of items that are displayed & at the same time, it holds the number of values in which the developer can implement.

# Loops

![For loop](https://i.ytimg.com/vi/L7nVZZQEnZU/maxresdefault.jpg)

## for loops
The for loop is a statement that specifies the conditions which are falsly evaluated in which the initial expression is executed, then the conditional expression is evaluated & then the statement is executed.

* for(i=0;i<5;i++)
* This example above is a simple for loop statement which indicates the initial expression which is (i=0), then the conditional statement implies that the i must be less than 5 & then the statement is completely executed

## while loop
While loop is based on executing the statements before evaluating the condition that states to be true. If the condition is false, the loop will stop executing & then passes the following statement.

* x = 0
* y = 0
* while (x < 5)
{
  x++;
  x+=y;
}

## Do while loops

[do while](https://www.w3schools.com/jsref/jsref_dowhile.)

It creates a loop that executes a block of codes before checking if the condition is true. Which means that those statements are processed whether the condition is met or no

## If else statements
[IF else](https://www.w3schools.com/js/js_if_else.asp)

They are based on conditional statements that if the value is true, then the code block is executed, but if its false, then the second code block will continue to run instead.

## Switch statements
[switch](https://www.w3schools.com/js/js_switch.asp)

They are similar to the if else statements in which this time the variable with a switch value. The switch statement is conditional because it consists of cases of variables in which if one case is false, it will continue to the next case. The difference between the switch & if else statements is the fact that the switch has a default option if none of the cases are matching with each other. Unlike the if else statment, the switch consists of the break statement which stops the rest of the coding process if the matching value is found true.