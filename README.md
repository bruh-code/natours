# Natours front-end web development project
Natours is a ficticious website of an nature tours agency. The website uses a lot of advanced CSS, and it has been well designed by Jonas Schmedtmann, the author of [advanced CSS course](https://www.udemy.com/advanced-css-and-sass/), this project is part of this course. See it [live here](https://bruno-lombardi.github.io/natours/), powered by Github Pages.

![Natours website](https://image.prntscr.com/image/JsplUNe_TfKsiWIJyDGB_w.png)

## Getting ready for development
### Fork the project and do the following
To start the development, you need to uncomment line 10 in index.html file. This way the linea.css file will load. Now, make sure you have [npm](https://www.npmjs.com/) properly installed in your system.
Then, just run these from your terminal:
```
npm install
npm run start
```
These commands will start the development server and watch for changes in the sass code, compile it and show the results instantly in the browser.

## Compiling for production
Now you should comment that line 10 in index.html file, as for production we will concat all the css in one file.
Then, just run:
```
npm run build:css
```
