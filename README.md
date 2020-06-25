# Project 0 - CS50

## Requirements:

- [x] At least four html pages
- [x] At least one list
- [x] At least one table
- [x] At least one image
- [x] At least one stylesheet file
- [x] at least five different CSS properties
- [x] At least five different types of CSS selectors (at least once: #id, .class).
- [x] At least one mobile-responsive @media query
- [x] At least one Bootstrap component
- [x] At least two Bootstrap columns for layout purposes using Bootstrap’s grid model.
- [x] At least once SCSS variable
- [x] SCSS nesting
- [x] SCSS inheritance
- [x] Readme info

## Content
### HTML pages:
This project has five HTML files that contains:
1. index: Home page. From here you can access to the "about" and other pages.
2. htm/git/css: These three pages contain a summary taken from the notes of the first two lectures of the CS50 web course. In this 3 files you can find the implementation of unordered lists, Boostrap grid model using two colums, a nav boostrap component and images.
3. about: This page contains info about the course and me. Also there is an implemetation of html tables.

### CSS files:
Into the css folder you can find 3 Stylesheets:
- style.css: This stylesheet is is applied to the home  page. Contains more than five css properties, five different types of css selectors and one `@media` query.
- nav.css: Contains the styles applied to navbar in all html pages.
- content.css: this file is the result of the compiled scss file. 
  
### SCSS
In this project there is just one scss file.
content.scss file contains the style applied to this three html files:
1. git.html
2. htm.html
3. css.html
   
Also there you can find the implementation of scss variables (`$size` variable), scss inheritance, scss nesting and one `@media` query. 

#### Compiling SCSS
To compile the content.scss file and keep on track the changes I followed the next steps.

1. **Install node.js**
2. **Initialize NPM**: In the directory of the project open a terminal and run the command `npm init`. Then a `package.json` file will be generated.
3. **Install Node-Sass**: Now you have to type on the terminal the command `npm install node-sass`. This package will allow you to compile the Sass file to Css.
4. **Writing the Node-Sass command**: In the `package.json` file into the script section you write the following code:
   
   ```
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "scss": "node-sass -watch scss -o css"
    }
   ```
5. Running the script: For run the script open the terminal and type the command `npm run scss`.
   
Now you can compile and keep on track the changes of your Sass file.