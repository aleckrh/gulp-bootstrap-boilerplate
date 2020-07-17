# Gulp Boostrap Boilerplate

A not so overkill front-end workflow environment or boilerplate... whatever you want to call it.

Fork, star or use it in your project.

## Requirements

- Node.js
- NPM
- Gulp

## Getting started

1. Clone repository:

- `git clone https://github.com/aleckrh/gulp-bootstrap-boilerplate`

1. Change directory:

- `cd gulp-bootstrap-boilerplate`

1. Install all node modules:

- `npm install`

- Make sure you can run `gulp -v` and `npm -v`

## Gulp Tasks

- `gulp` the default task that builds everything
- `gulp watch` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp css` compiles SCSS files into CSS and minifies the compiled CSS
- `gulp js` minifies the themes JS file
- `gulp vendor` copies dependencies from node_modules to the vendor directory

## Dependencies

```js
"devDependencies": {
  "browser-sync": "^2.26.9",
  "del": "^5.1.0",
  "gulp": "^4.0.2",
  "gulp-autoprefixer": "^7.0.1",
  "gulp-clean-css": "^4.3.0",
  "gulp-concat": "^2.6.1",
  "gulp-header": "^2.0.9",
  "gulp-html-replace": "^1.6.2",
  "gulp-plumber": "^1.2.1",
  "gulp-rename": "^2.0.0",
  "gulp-sass": "^4.1.0",
  "gulp-sourcemaps": "^2.6.5",
  "gulp-uglify": "^3.0.2",
  "merge-stream": "^2.0.0"
},
"dependencies": {
  "bootstrap": "^4.5.0",
  "jquery": "^3.5.1",
  "popper.js": "^1.16.1"
}
```

## License

Code licended under the [MIT](LICENSE) license.
