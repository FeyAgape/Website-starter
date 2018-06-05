# A Sass project Template with a sass directory. 

The template already has a file structure and a gulpfile.js file, and Gulp and Sass is already required in the gulpfile and a gulp task has been created for them however, you have to install gulp and sass into your project directory.

## To use: run the following code in the command line

1. run the npm init command from inside the directory:
` npm init`

npm init will prompt you: to enter the project name, version, description, etc

**Example** 

`package.json:`

`{
  "name": "project",
  "version": "1.0.0",
  "description": "This is a gulp project",
  "main": "index.js",
  "scripts": {
    "test": "echo"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/Username/Project.git"
  },
  "author": "First-name Last-name",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/Username/Project/issues"
  },
  "homepage": "https://github.com/Username/Project#readme"
}`


2. You’ll have to install gulp within the project folder by augmenting the install code slightly:

`npm install gulp --save-dev`


3. We can compile Sass to CSS in Gulp with the help of a plugin called `gulp-sass`. You can install gulp-sass into your project by using the npm install command like we did for gulp.

We'd also want to use the --save-dev flag to ensure that gulp-sass gets added to devDependencies in package.json.

`$ npm install gulp-sass --save-dev`