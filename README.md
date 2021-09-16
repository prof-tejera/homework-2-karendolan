# React - Dev Setup and Deployment

This assignment is intented to help you set up your development environment for React. You will create a simple React App and deploy using one of the methods covered in lecture.

## Step 1
- Install `npx` following the instructions here: https://www.npmjs.com/package/npx
- run `npx create-react-app my-first-app` to create the React application
- In the newly created app, replace the contents of `App.js` including your name:

```
import './App.css';

function App() {
  return (
    <div className="App">
      <header className="App-header">
        <p>Hello CSCI E-39!</p>
        <p>
          My name is ____________
        </p>
      </header>
    </div>
  );
}

export default App;
```

- run `npm install`
- start the app with `npm start`
- verify the app is running

## Step 2
Deploy the application using one of the methods covered in class: Github Pages, Render, or AWS. If you prefer to use a different service, explain your choice and process.

## Submitting

- URL to live application: <https://homework-2-karendolan.onrender.com> 

- How did you deploy it?
	* npm run build in ./my-first-app directory
   * Remove ./build from .gitigmore, 
   * Commit build diretory, push to main
   * Signup for a Render.com account
   * Add a link to this repo to the free Render static site
   * Reference the ./my-first-app/build for the static files
   * Let Render clone and push the static files

- What code editor are you using?
	* Atom.io

That is all!
