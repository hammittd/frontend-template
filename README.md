# Get Started
A skeleton to help make getting started with webpack, babel, react, redux, and associated dependencies and devtools faster 🚀

In your terminal, run:
```
git clone https://github.com/dhammitt/project-init-skeleton.git
```

### Babel
- @babel/cli
- @babel/core
- @babel/plugin-proposal-class-properties
- @babel/preset-env
- @babel/preset-react
- babel-loader
### Webpack
- Webpack
- webpack-cli
- webpack-dev-server
- webpack-merge
- clean-webpack-plugin
- html-webpack-plugin
- Includes a development config for webpack with hot reloads:
```javascript
webpack.dev.js
{
  mode: 'development',
  devtool: 'inline-source-map',
  devServer: {
    contentBase: './dist'
}
```
## Directory Structure:
```
.
├── config
│   ├── webpack.common.js
│   ├── webpack.dev.js
│   └── webpack.prod.js
├── package-lock.json
├── package.json
└── src
    ├── index.html
    └── index.js
```
