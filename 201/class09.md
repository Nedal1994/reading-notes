# Class 09 summary

![forms](https://www.tutorialbrain.com/wp-content/uploads/2019/01/HTML-Form.jpg)

HTML forms are a set of collecting inputs in which it is sent to the server for processing. Forms are made for enabling users to search & perform certain functions such as registration, logging in, etc...Forms also have a certain amount of form controls for collecting information & they include adding texts, adding choice buttons (radio buttons, checkboxes, dropdown boxes), submitting buttons uploading files & vice versa.

Forms work in a way that when the user fills it & presses a submit button that sends the information to the server.

![forms](https://miro.medium.com/max/1838/1*mUAA2_0ZCGJeR_tXIv9s0g.png)

The forms are structured with the **form** tags which carry the action attribute & the method. The action attribute is based on the value of the page's URL in which the server will receive the information when the user submits it.

![method](https://static.javatpoint.com/servletpages/images/get-vs-post.jpg)

The method attribute is based on specifying how the data is sent to the page regarding the action that has been taken in the form. The method attribute consists of 2 methods:
* GET - The GET method is based on requesting the data from a resource in which the browser asks the server to send back the resource in which the body element becomes empty.

* POST - Unlike the GET method, the POST method is based on sending the data to the server to create or update the resource & it is the most common HTTP methods.

![input](https://css-tricks.com/wp-content/uploads/2017/06/required-input.png)

The input element is used to create different form controls that specifies an input field in which the developer can insert the data in it. Depending on the developer's choice, the input elements consists of types that control the form such as button, text,checkbox, password, radio, reset, search, etc...

![buttons/boxes](https://miro.medium.com/max/968/1*Eykm7L4j3HMrdnRynsoRGQ.png)

One of the most interesting things that users are always aware of is the fact that whenever they're on a specific website & they fill forms or register for a certain occupation, those websites consists of radio buttons & checkboxes. Radio buttons are multiple choice buttons which allows the user to choose one choice of options while checkboxes are square shaped boxes which allow the users to select more than one choice of the options given.

![dropdown](https://www.jqueryscript.net/images/jQuery-Plugin-To-Convert-Html-Lists-Into-A-Dropdown-List-NavToSelect.jpg)

Like the radio buttons & checkboxes, dropdown menus are commonly used in many websites & like the radio buttons, it allows the user to see through the listed options & select one option at a time.

![file](https://i.stack.imgur.com/JNNuX.png)

Another interesting factor in the HTML forms is the fact that users can upload their files on specific websites for conversion or submitting purposes such as mp3, document files, videos, etc...

![list styling](https://www.w3.org/wiki/images/5/5e/Referenc.gif)

When it comes to ordered & unordered lists, the first thing that comes in mind is the fact that those lists consists of numbers & symbol. There's a method of making those numbers & symbols appear & never appear. For example, the unordered list consists of bullet point symbols & the developer can change that by using the **list-style-type** property which allows the developer to control the shape of the bullet points.

![html tables](https://i.stack.imgur.com/VCxSJ.png)

HTML tables allow the developers for data arrangement by inserting them in rows & columns. The HTML table is defined with the **table** tag & for each row it is defined with the **tr** tag & each table header is defined with the **th** tag & each data is defined with the **td** tag. For styling tables, developers can use borders either through the HTML or CSS in which the border lines can be thicker or thinner depending on the developer's choice.

![table style](https://res.cloudinary.com/practicaldev/image/fetch/s--Zhu5E2Bm--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://dev-to-uploads.s3.amazonaws.com/i/02lxssgxrwv7ywp2lhix.jpg)

Styling the tables is similar to the list styling except the fact that it specifies the size, borders, headings, rows & table data.

## Javascript events

![events](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/Ways-of-Using-JavaScript-Events-1200x720.png)

Javascript events are based on things that happen to HTML elements in which the javascript can react to. These events are things that either the user or the browser does. There are types of events that the user does when browsing the web & they trigger a function in the user's javascript code. Here are a list of events that can be implemented in the HTML:
* load
* unload
* scroll
* click
* input
* submit

The events trigger the javascript if the user interacts with the HTML on the website in which the process works by 3 steps:

1. Selecting the elements which the user writes teh script for a response.

2. Indicating which event will trigger the response.

3. Stating the code that the user wants to run the event that occurs.