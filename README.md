# Voting Client

### 1. Client Project Setup
```
mkdir voting-client
cd voting-client
npm init -y
```
We're going to use [Webpack](http://webpack.github.io/) along with its development server, so let's add both to the project:
```
npm install -g webpack webpack-dev-server
npm install --save-dev webpack webpack-dev-server
```
Since we're going to use both ES6 and React's [JSX syntax](https://facebook.github.io/jsx/) in the client code, we need some tooling for those. Babel knows how to process both, so let's plug it in. We need both Babel itself and its Webpack loader:
```
npm install --save-dev babel-core babel-loader babel-preset-es2015 babel-preset-react
```