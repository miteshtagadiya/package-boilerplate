```
{
  "name": "boilerplate",
  "version": "0.1.0",
  "private": true,
  "dependencies": {
    "react-scripts": "1.1.4"
  },
  "scripts": {
    "start": "webpack-dev-server --mode development",
    "test": "react-scripts test --env=jsdom",
    "eject": "react-scripts eject",
    "transpile": "babel src -d dist --copy-files",
    "prepublishOnly": "npm run transpile",
    "build": "webpack --mode production",
    "deploy": "gh-pages -d examples/dist",
    "publish-demo": "npm run build && npm run deploy"
  },
  "description": "This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).",
  "main": "dist/index.js",
  "peerDependencies": {
    "react": "^16.3.0",
    "react-dom": "^16.3.0"
  },
  "devDependencies": {
    "babel-cli": "^6.26.0",
    "babel-core": "^6.26.3",
    "babel-loader": "^7.1.4",
    "babel-preset-env": "^1.7.0",
    "babel-preset-react": "^6.24.1",
    "css-loader": "^0.28.11",
    "gh-pages": "^1.2.0",
    "html-webpack-plugin": "^3.2.0",
    "react": "^16.4.1",
    "react-dom": "^16.4.1",
    "style-loader": "^0.21.0",
    "webpack": "^4.15.0",
    "webpack-cli": "^3.0.8",
    "webpack-dev-server": "^3.1.4"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/miteshtagadiya/package-boilerplate.git"
  },
  "keywords": [
    "boilerplate",
    "code",
    "for",
    "package"
  ],
  "author": "Mitesh Tagadiya",
  "license": "MIT",
  "bugs": {
    "url": "https://github.com/miteshtagadiya/package-boilerplate/issues"
  },
  "homepage": "https://github.com/miteshtagadiya/package-boilerplate#readme"
}

```

```jsx
npm install

npm run transpile

npm run build

npm run deploy

npm run publish-demo
```