## ProductHired coaching
Coaching is vital to your career growth, and we believe the best way to connect mentors with mentees is through a platform where they can find each other. It will be a two-way market in which mentors can:
1) Post your profile
2) Indicate the skills and knowledge they would like to teach
3) Choose whether their services are free or paid.
4) How many sessions will be and how they will be held, etc.
Users will be able to view mentors in a separate section of the site based on filters. Agree on a session and pay for it using PAyPal.

## Design






This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify


## Structure of project

#### .STORYBOOK folder

This folder for storybook dependency, you can see live components preview


#### NODE_MODULES folder

Contain all project dependencies files


#### PUBLIC folder

Project static files (index.html, favicon.ico, etc...)


#### SRC folder

This is the main project folder for development. It contains components, storage, actions, styles, etc... .


#### .ENV .ENV.DEVELOPMENT .ENV.STAGING

Files responsible for build app, they store the basic project constants for build

.ENV - this file is used when starting app locally

.ENV.DEVELOPMENT, .ENV.STAGING - this files used when build app to production


#### addPreloadLinks.js

Used in package.json scripts to add attribute 'preload' <link>, to improve perfomance


#### package.json

All project dependencies and npm scripts


#### jsconfig.json

Settings to use absolute import paths in js files


#### .gitignore

Paths that do not need to be included in the repository



## SRC folder structure

#### ACTIONS folder

Contains all `Redux` actions


#### ASSETS folder

Contains images folder, styles(scss) folder, fonts folder


#### COMPONENTS folder

Contains all React `Components` (layout, pages, shared and single components)

`layout` - contain main components to make base layout
`pages` - contain main pages components
`shared` - contain reused components


#### CONSTANTS folder

Contains all used constants in project


#### REDUCERS folder

Contains all `Redux` storage reducers


#### ROUTES folder

Main componet with all project routes(pages)


#### STORE folder

Contains init `Store` files


#### UTILS folder

Contains common functions used in project


#### HISTORY.js file

Project history(browser history) initialization


#### index.js file

Project enter point, main file
