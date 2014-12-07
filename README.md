# BLANKULAR: THE HEROKU FRIENDLY ANGULAR BOILERPLATE

Combining the usefulness of Angular and Heroku together for those of us who aren't deployment pros.  This boilerplate is designed to be all client-side, no database behind it.  Imagine the possibilities!

## Getting Started With Blankular:

1.  Clone this repo.
2.  CD into your directory and type in "npm install".
3.  Then type in "bower install".
4.  in the package.json file, fill out all of the appropriate fields, marked in brackets and uppercase type.
5.  Then CD into the CSS subdirectory under the app directory, and type in "sass --watch styles.scss:styles.css"
6.  now CD up to the root of your project and type in "npm start".
7.  Check out your brand new project locally!

**That's all there is to it to get started on your new project. Baller.**

## Notes on file organization:

#### Directives and Controllers.

These are in their own scripts rather than in the app.js file.  You can find them in the JS directory.

#### Sassy CSS.

The Sass files have been set up as partials.  Add, remove or modify as you see fit.

#### Bower it up!

Install whatever you want with this, the only things installed via Bower was Angular itself.

## Notes on deployment:

The reason Blankular exists is to make life easier for those of us who are not necessarily familiar with Heroku and Node.js.  All of the files have been set up to eliminate confusion.

Simply make sure that all the fields have been filled in correctly in the package.json file and that you have your GitHub repository set up and going.  Then follow the instructions listed [here.](https://devcenter.heroku.com/articles/getting-started-with-nodejs#introduction)

(You could probably also FTP this to any server you want if you want to go ULTRA easy.)

**In Closing, Blankular exists because I like you, Angular and Heroku.  If you note any bugs, issues, or have any polite commentary, find me in the package.json file and say hello!**
