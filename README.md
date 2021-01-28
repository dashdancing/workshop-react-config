# workshop-react-config

### This is the React Workshop repository.

### We are going to make a weather app with the login feature :smile:

#### Objective

Build a simple application throughout the sessions and to know the best practices to be able to use React in our projects. 
Coach mentor Oscar shared with us some hacks that can facilitate our work as developers.
Recap concepts & solve doubts.  

##### In the first session on Tuesday, January 26, we learned:

- First steps to create our base app with react
- Import libraries to manipulate the DOMThe usefulness of babel in our 
- JavaScript projects
- Configure Webpack
- Questions about how to order our files and folders directory were resolved
- Check that everything is ready to go

##### In the second session on wednesday, January 27, we learned:

-Create and manage routes for the login.

- In our component / function in App.jx we create a component to which to pass the data, create the logic to return the routes. These routes will be contained in the <BrowseRouter>.
  
- In the folder "containers" we add the logic components for our login.

- Using RequireAuth to validate if a user is authenticated and send it to <RequireAuth> where we will have the private routes. If a user is not logged in, he is redirected to / home.

- This is the flow that our application: UI --> Action --> Reducer --> Store --> UI

Tips:

> With the "resolve" property of Webpack we can use aliases for the paths of our directory. This can include an "@" to identify that it is an alias.

> With the tool https://github.com/js-cookie/js-cookie we can bring values from cookies.

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
