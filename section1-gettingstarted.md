#### Section 1 - Getting Started 

###### What is React? 

React is a javascript library. It's about building javascript driven apps. React apps run on the browser, they don't run on the server. 

This is really advantageous, as things happen instantly, we don't have to wait for a server response. 

User interfaces is what a webpage user sees and react is all about using components to build these user interfaces. 

If we think about it, any webpage can be split into components. If we split our websites into components, we can build these components as contained pieces of code. We can split things up. This makes it easier to work in teams and also to work by ourselves. This also makes it easier for us to reuse our code! 

In the end, our components can be thought of as just custom build HTML elements.

###### Writing Our First React Code

Babel is a pre-processor that allows us to write what looks like html into a javascript function and return that to the user. This is how react works, it's called JSX and it's just syntactical sugar, that runs behind the scenes that gets compiled into normal javascript code. 

React allows us to write reusable code, which is great for a developer! 

###### Why React? 

1. React helps us with a problem that we have in use just plain javascript. This is that the UI state becomes difficult to handle with vanilla JS. It bigger JS apps, you have to manually target elements in the dom and if you then change the structure of your html code, chances are you need to change the way you target elements because you use querySelector. Even if you use JQuery, it's still something you have to keep in mind. If you have dynamic apps, this becomes really difficult! React helps us by making UI state management a non-issue. 

2. It helps us focus on business logic not on preventing our app from exploding. React is maintained by a big community, therefore, it's really good. 

3. React features a huge ecosystem, active community and is high peformance. This means that for any given problem we face, there is a good chance that we will be able to find a solution! 

###### React Alternatives 

There are alternatives to react. The major alternatives are Angular and Vue.js. All three of these frameworks are really good. JQuery is not an alternative to these frameworks. Its more about working with the dom. 

###### Understanding Single Page Applications and Multi Page Applications 

When we talk about frameworks, it's important to know that we can build two different types of applications. Single page applications and multi page applications. What's the difference? 

1. Single Page Application 

In a single page application, we only have one HTML page, content is re-rendered on client. 

In single page applications, our page is built up with components, and every component is a react component with the page itself managed by a root react component. 

We typically only have one ReactDOM.render() call this is because it is a single source of truth. 

This is the most popular way of building apps and is what we are going to use it in this course! 


2. Multi Page Application

In a multi page application we get back multiple html pages, where each page has the given url we have visited. The url will give us back different pages from each other. 

In a multi-page component, a lot of our page is just going to be html and css and some react stuff that we dump in. The complete page is also not under the overall control of react. 

We have multiple ReactDOM.render() calls. 

###### How to get the most out of this course. 

1. Code Along! 
2. Check source code if we are having issues! 
3. Ask and Answer in the Q and A section. 
4. Practice, practice, practice! 

