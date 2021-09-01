# Read05 Summary

![image](https://reactjs.org/static/1071fbcc9eed01fddc115b41e193ec11/d4770/thinking-in-react-mock.png)

React is very popular in terms of building bigger & faster web applications with Javascript & it is very scaled with Facebook & Instagram. React consists of things that makes you think about the applications that you want to build them, but the process takes a lot of time & effort to get it done properly. To think about building the website using React, the first thing the developers must do is to break the UI into component hierarchy, then build a static version in React, then identifying the minimal representation of the UI, then identifying which component is updating its own state & lastly adding an inverse data flow.

![ui](https://static.packt-cdn.com/products/9781785889769/graphics/05a482ed-fb83-4d81-a4f6-1bb0ee61462b.png)

1. **Changing the UI into component hierarchy**

Like the HTML wireframe, the React works the same method as HTML except that is divided into components that contain React JS programming codes based on web design & programming. When it comes to file or source handling in HTML it's no strange that we insert codes of getting the files or image sources simply using *img src*. However in React it works similar to HTML in gathering the sources, but this time the developer must insert a JSON file which contains all the sources of data that needs to be implemented on an advanced level.

2. **Building a static version in React**

![image](https://images.indepth.dev/images/2021/04/Building-a-React-Static-Site-Generator-1.jpg)

Once the concept of the React components are done, the next most crucial step is to build a static version of React because it is a mandatory process which takes the data models to render the UI. Building the static version of React requires using the props method which means that it passes the data from the parent component to the child component.

![image](https://res.cloudinary.com/practicaldev/image/fetch/s--xKWyj8SG--/c_imagga_scale,f_auto,fl_progressive,h_500,q_auto,w_1000/http://live-linguine-code.pantheonsite.io/wp-content/uploads/2019/03/react-state-vs-props.jpg)

The difference between the props & state is the fact that props can read the data & pass it from one component to another & it cannot be modified. The state method can be modified with *this.setState()* & it is managed by the component

3. **Identifying the incomplete representation of the UI state**

This process works by simply illustrating a simple unfinished design of the application, but to make sure that the UI is interactive the most important thing is to change the data model which requires the use of the state method in React. For developers to build the application properly, the first & most crucial key is to never repeat yourself or in this case *Don't Repeat Yourself (DRY)*. DRY is a principle in software development which aims at reducing the duplication of software patters which are replaced with abstraction or data normalization. To further improve building the application, the developers must do the TODO list which are actually programming processes that needs to be done properly.

4. **Identifying where the state methods should be placed**

The components changes its own state & React has always been about a one method data flow down the component hierarchy. The state methods must identify every component that renders something based on that state which finds a certain component which is needed in the hierarchy.

5. **Add inverse data flow**

![image](https://res.cloudinary.com/practicaldev/image/fetch/s--3krQwEN0--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://i.imgur.com/GUuOmwI.png)

This is the last step of building an application in React which is adding an inverse data flow. This process works by supporting the data flowing the other way because in React makes it easier to understand, but it does require more programming than usual.