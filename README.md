# Gulp 4 Boilerplate Repo

Boilerplate primarily for setting up a project with Gulp, but also to serve as a blank template for a frontend project.

Gulp is setup to accomplish:

- Compile scss files to css
- Autoprefix and minify css file
- Concat the js files
- Uglify(parse, minify, compress) js files
- Pipe the final css and js files to the `dist` folder

## Quickstart

- Clone Reop
- Install Node.js
- Run npm install
- Run gulp to run the default Gulp task

## Instructions

- install node
- open terminal run `npm install --global gulp-cli`
- run `npm init -y`
- run `npm install --save-dev gulp gulp-sass gulp-sourcemaps gulp-postcss autoprefixer cssnano gulp-concat gulp-uglify gulp-replace`
- create a new file in the root of the project named `gulpfile.js`
