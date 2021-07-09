# Class 06 Summary

## Objects

![](https://miro.medium.com/max/1400/1*iKJx57JU9sKdff-Os7upyA.png)

![](https://raw.githubusercontent.com/3dbeb41841bfbfcc24d55143816cf7f1/js-objects-and-json/master/images/object-property-method.jpg)

Computers use javascript to create models of the world using data processes which help define the objects & properties. Objects are based on physical things that can be represented to anyone while properties are based on the characteristics of the objects which consists of a name & value.

![](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object-oriented_JS/mdn-graphics-instantiation-2-fixed.png)

Objects also consists of methods which represent things that people need to do with objects in which they can update the values of the object's properties. 

Fitting HTML, CSS & Javascript all together is a mandatory method which allows the user to edit the options in terms of design, scripts & elements arrangement. Javascript works in HTML 2 ways:
* Link the js file in the HTML file
* Implement the script tag inside the HTML file & implement javascript codes

[Literals](http://www.standardista.com/javascript/javascript-object-literals-simplified/)

Literal notation is the easiest for creating objects & it has properties for creating objects such as dot notation & bracket notation.

![notation](https://bunlong.github.io/assets/img/dot-notation-vs-bracket-notation-to-access-object-properties-in-javascript.png)

Dot notation is based on specifying the object followed by a dot followed by a property name such as objectname.propertyname

Bracket notation works similar to the dot notation except the fact that the object is followed by square brackets such as object[property]

## Document Object Model

![dom](https://www.w3schools.com/js/pic_htmltree.gif)


Document Object Model or DOM is a representation of the HTML which defines the standards for accessing documents in which the javascript can program the changes of the document structure & content. The purpose of the DOM is to mirror the HTML as in memory representation whuch is composed of objects that are combined with each other & an interface which allows modification for the objects.

![elements](https://lh3.googleusercontent.com/proxy/L5YGmVd7374oxojV52hg6sXMY7fQ6J3oJwlZuA3NXQT3RXXLr3TgpBAwuR2PZTmPugiNAzR6OudTJ3nrNnpd5HDAaw)

DOM is accessable by returning an element or NodeList which is a collection of nodes. Nodes are classes  which are abstract in which consists of subclasses & the most notable that is used to describe the node are document, element & the document fragment. The node includes attributes & data types such as texts, comments & vice versa.

The element nodes can be returned by inserting those tag names:
* getElementById('id') - It selects the elements based on its id attribute

* querySelector('css selector') - It selects the css selector which takes one or more elements.

* getElementsByClassName('class') - It selects the element regarding its class attribute

* getElementsByTagName('tag name') - It selects the elements that has a specified tag name

![nodelist](https://i.stack.imgur.com/t2ph3.png)

There are 2 methods to select the element from a NodeList:
* Item method - elements.item(0)

* Array method - elements[0]

To repeat the actions for the whole nodelist is to loop through each node by applying the same statement to each of them such as:
* for(var i=0; i < items.length; i++)


![traverse dom](https://www.qualitestgroup.com/images/howto/DOMTree_HowTo.png)

Traversing the DOM is based on selecting the element node which allows the developer to use the parent or ancestor element which go all around the DOM tree easily

[innerHTML](https://www.w3schools.com/jsref/prop_html_innerhtml.asp)

The innerHTML property is based on returning the HTML content of the element. The way this property works is getting the content of the element & return it as a long string which includes markups that the element contains.

[DOM manipulation](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents)

DOM manipulation is baed on using the DOM for controlling the HTML styling & information which makes heavier by using the document object. However, the manipulation process works by adding & removing elements. Adding element uses the techniques which allows the developer to create the element, the text node & append the child element.

* createElement() - This step is based on creating the element in which the node is stored in a variable

* createTextNode() - It creates a new text node & it is stored in a variable in which it provides the content for the element.

* appendChild() - It specifies the element that the developer chooses to add.

* removeChild() - This method is based on removing the element node.

## Cross site scripting attacks

![xss](https://www.imperva.com/learn/wp-content/uploads/sites/13/2019/01/sorted-XSS.png)

As web developers, we must be aware of any types of attacks that could damage the HTML coding process among them is the Cross Site Scripting (XSS) attacks. They are based on a web security weakness which allows the attacker to compromise the interactions that users have with a vulnerable application. It happens if the developer adds to the HTML page using innerHTML & several jQuery methods in which the attacker places malicious codes into the website such as creating profiles & comments & files can be uploaded such as images & videos.

For users & developers to prevent themselves from xss attacks is to ensure avoiding dangerous websites & being aware of the situation. A tip for preventing those attacks is to install internet security programs to santize the HTML pages & protects the users by simply preventing them from entering.

## The difficult part of programming domains

When it comes to programming, its no question that the hardest part of it is the fact that a person studies it & then later on forgets everything. However, if the person is capable to study & take notes of the basic programming codes, then there's an opportunity for him/her to get to know the difficulty in programming by simply working on it & finding solutions for its problems. To make the problem domain easier is to make sure to take more notes to get better understanding of the situation which allows him/her to solve, but at the same time it will allow the user to be better at programming later on.