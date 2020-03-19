# github-battle
Its an Basic React App for Learning React of the Website TylerMcginnis

run those commands
npm install --save-dev @babel/core @babel/preset-env @babel/preset-react webpack webpack-cli webpack-dev-server babel-loader css-loader style-loader html-webpack-plugin

npm install react-icons
npm install query-string
npm install react-router-dom
npm install babel-plugin-syntax-dynamic-import (add syntax-dynamic-import to plugins section of babel in package.json file)

for production in package.json -> "build": "NODE_ENV='production' webpack"
                          for windows-> "build": "SET NODE_ENV='production' && webpack"
                          
                          and in webpack.config.js
                            mode: process.env.NODE_ENV==='production' ? 'production' : development',
                            
                            npm install --save-dev copy-webpack-plugin
