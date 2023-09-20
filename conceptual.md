### Conceptual Exercise

Answer the following questions below:

- What is the purpose of the React Router?
it lets us handle routing when using React.

- What is a single page application?
it's when we load one page, and just constantly update the body of that page without reloading or loading a new page, just re-rendering components.

- What are some differences between client side and server side routing?
client side does all the routing on their side and not sending a request to the server to refresh or redirect the page, but keeps the page the same and is essentially a single page application.

- What are two ways of handling redirects with React Router? When would you use each?
history.push and <redirect/>.
Using history.push requires less code and using. <Redirect /> follows the core principle of React (state change => re-render). Which you use is ultimately up to you.


- What are two different ways to handle page-not-found user experiences using React Router? 
using the default browser 404 page. or creating a custom one using react-router-dom.
​​​​​​Browsers have a default 404 page but creating a custom one allows you to tell your users what went wrong and how they can fix it. You can easily create a React 404 page for all URLs that don’t exist in your web app using a react-router-dom. You can also style it according to your brand.

- How do you grab URL parameters from within a component using React Router?
Using React Router, when you want to create a Route that uses a URL parameter, you do so by including a : in front of the value you pass to Route 's path prop. Finally, to access the value of the URL parameter from inside of the component that is rendered by React Router, you can use React Router's useParams Hook.

- What is context in React? When would you use it?
Context provides a way to pass data through the component tree without having to pass props down manually at every level.
When you want to pass via props context can do it without having to pass down to every single child of a child of a child of a child of a child, so you don't have to keep on keepin' on.

- Describe some differences between class-based components and function components in React.
Class base is how it was initially done, but the issues with that were solved and made easier with hooks.

- What are some of the problems that hooks were designed to solve?
Hooks were created to solve three problems: wrapper hell, huge components, and confusing classes.