# webpack-learning
webpack-learning : Steps to include different modules in webbpack and use them in project. Like css, sass, modules.

npm i -D webpack "-D is here to represent dev mode, -P for prod mode"

webpack ./src/app.js  ./dist/app.bundle.js -p --watch "src and destination path to make bundle file"

npm i html-webpack-plugin --save-dev

npm install css-loader --save-dev