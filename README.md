# Attractor frontend test task

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Project Tech Stack 
1. React.js
2. Material UI
3. Styled components
4. Redux
5. React-router version 6
6. Axios 

## Available Scripts

In the project directory, you can run:
### `git clone link_my_project`

### `yarn install`

It installs all required dependencies included in package.json file

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!


# Project rules and Style guides

### Folder structure
#### `src/assets`
This folder contains subfolders: `styles`, `icons` and `images`.

#### `src/components`
This folder contains reusable stateless and stateful components. It has following sub folders:
#### |---`src/components/UI`
     This folder containes common presentational components(eg. Button, Input, etc.) 
  
#### |---`src/components/Repositories/CreateRepositories.jsx`
     Inside `src/components` we may have also other domain specific components like `src/components/Post/PostRepositories.jsx`

#### `src/containers`
Each page includes many small components. This folder is similar to src/components, but it contains our large components which is literally our app pages.

#### `src/utils/constants` 
This folder to define some objects or arrays and import them anywhere we want to use. These constants could be list items or some text or some words. This is a      good practice to keep them separate from components.

#### `src/utils/helpers`
We can define helper functions in this folder. There are some functions that we might need across application which generate some certain data or do something special. It’s better to keep them separate from components in order to make them reusable and make code cleaner.

#### `src/layout`
It contains the layout components*.
Layout is the common top wrapper component usually will contain Navbar , Sidebar and Children components

#### `src/store` 
All type definitions, actions, reducers and the redux store belong to this folder.

#### `src/routes`
We’ll need this folder for react-router configs and route related components.



## Style Guide

#### Linters
We are using Eslint and prettier linter tools to find bugs and errors before they happen.
We'll spend less time testing new features and team's code will be more consistent.
We are following AirBnB JavaScript style guide


#### How to deploy a project?

1) git clone link_my_project
2) yarn install
3) yarn start
