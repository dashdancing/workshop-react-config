# workshop-react-config

### This is the React Workshop repository.

#### We are going to make a weather app with the login feature :smile:

#### Objective

Build a simple application throughout the sessions and to know the best practices to be able to use React in our projects. 
Coach mentor Oscar shared with us some hacks that can facilitate our work as developers.
Recap concepts & solve doubts.  

# Stack
![JavaScript](https://img.shields.io/badge/_-Platzi-292e33?style=flat-square&logo=platzi&logoColor=fff)
![JavaScript](https://img.shields.io/badge/_-JavaScript-292e33?style=flat-square&logo=javascript&logoColor=fff)
![React](https://img.shields.io/badge/_-React-292e33?style=flat-square&logo=React&logoColor=fff)
![Webpack](https://img.shields.io/badge/_-Webpack-292e33?style=flat-square&logo=webpack&logoColor=white)
![Babel](https://img.shields.io/badge/_-Babel-292e33?style=flat-square&logo=Babel&logoColor=white)

# Installation
Install dependencies
```bash
npm install
```
Build project
```bash
npm run build
```
Run project
```bash
npm run start
```

# Contributors
###### Contributions are welcome! Just send a pull request :smile: 

<table>
  <tr>
    <td align="center"><a href="https://jcmexdev-blog.herokuapp.com/"><img src="https://avatars.githubusercontent.com/u/24815945?v=4" width="100px;" alt=""/><br /><sub><b>J. Carlos García</b></sub></a></td>
  </tr>
</table>

#Sessions thread

##### In the first session on Tuesday, January 26, we learned:

- First steps to create our base app with react
- Import libraries to manipulate the DOMThe usefulness of babel in our 
- JavaScript projects
- Configure Webpack
- Questions about how to order our files and folders directory were resolved
- Check that everything is ready to go

##### In the second session on wednesday, January 27, we learned:

- Create and manage routes for the login.
- In our component / function in App.jx we create a component to which to pass the data, create the logic to return the routes. These routes will be contained in the <BrowseRouter>.
- In the folder "containers" we add the logic components for our login.
- Using RequireAuth to validate if a user is authenticated and send it to <RequireAuth> where we will have the private routes. If a user is not logged in, he is redirected to / home.
- This is the flow that our application: UI --> Action --> Reducer --> Store --> UI

##### In the third session on thursdar, January 28, we learned:

- Introduce redux to the project.
- Bring the data of our login form.
- Redux offers us a single source of truth.
- Make use of Useref to bring particular values to our Login component.
- The useRef hook has its origin in the createRef method that is used in class components and that allowed to create a “reference” to a DOM element created during rendering.

##### In the four session on friday, January 29, we learned:

- Using React Context to encapsulate a piece of state in a context that is injectable anywhere in our component tree.
- The Context in React 16.3 works in a similar way. For it to work we need a Provider and a Consumer. The first thing we will do is create our new context, adding the following code:
  ```javascript
  const AppContext = React.createContext ();
  ```
- The next thing will be to create our Provider, the place where our data will live. With the value property we will pass the data we want to access in our application.
- Our Provider should always be the highest level component in our application.
- Make use of the Provider that will have a virtual value property that will notify its changes through an event.

Tips:

> With the "resolve" property of Webpack we can use aliases for the paths of our directory. This can include an "@" to identify that it is an alias.

> With the tool https://github.com/js-cookie/js-cookie we can bring values from cookies.

> Restart our server every time we put an alias.

> The chaining operator function of ECMAScript 6 prevents our application from breaking if a data does not exist.

> Redux is not exclusively about React but the community associates it because Dan Abramov is the creator of React and Redux.

> Code Spell Checker is a plugin that helps us avoid the types and works as a spell checker and we can include terms in Spanish to its dictionary
