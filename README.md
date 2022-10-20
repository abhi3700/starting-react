# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## About

- Github pages deployment
- Pokemon search App

## Learning

- [v1: Pokemon Search with table header & a row](https://github.com/abhi3700/starting-react/commit/910f3ee62562a56526242683893c666651207ca7)
- [v2: Pokemons populated in a table](https://github.com/abhi3700/starting-react/commit/162cd6416ba8bedc9a4d3caffe365ae7c5d881a6)
  ![](img/v2_demo.png)
- [v3: 20 Pokemons populated in a table](https://github.com/abhi3700/starting-react/commit/954d132b509e89db3c3040d1751223487f1aebd5)
  ![](img/v3_demo.png)
- [v4: refactored the code with component](https://github.com/abhi3700/starting-react/commit/dc8cdb29719ccbdc2ae949fdbefb826d1c689d07)
  ![](img/v3_demo.png)

## Deployment

### Github Pages

> Always create a github repository for a new project in order to deploy it to **Github Pages**. Otherwise, it's going to be a mess with the static folder getting pushed to the provided github repository url.

1. Edit the [`package.json`](./package.json) with this:

```json
"homepage": "https://<your-username>.github.io/<your-repo-name>",
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build",
```

2. Install `gh-pages` dependency using `$ npm i --save gh-pages`
3. Run `npm run deploy` & then `build` folder gets generated. And this `build` folder shall be uploaded into a separate branch called `gh-pages`'s root in the github repository url.

![](img/react-github-pages-deploy-settings.png)

![](img/react-github-pages-deploy.png)

From now on, you can view the output with the changes made deployed to the github pages url with the commands `$ npm run deploy`.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

## References

- [By Jake Herrington YT playlist](https://www.youtube.com/watch?v=MJaGti42c5c&list=PLNqp92_EXZBJ4CBroxVBJEpAXoz1g-naZ)
