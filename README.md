# boilerLess (version 0.7.0)
Based on HTML5 Boilerplate, **boiler{LESS}** is an elementary LESS boilerplate for easy webproject setup.

## Basical Style and More
**boiler{LESS}** provides a common style for all commons html elements such as: html, body, h*, p, a, ul, ol, img, span, small, form, input, select, textarea and much more.<br>
You can setup any custom fonts or colors you need and use many useful mixins that make your work faster.

## Installation
Install and use **boiler{LESS}** is very simple:
* download the main package
* uncompress *.zip/.tar.gz pack* on your local drive
* enter the **boilerLess** dir
* now edit the *index.html* file and place your markup inside it
* now enter the less dir, edit the **boilerLess-variables.less** using your custom value for each available less variable
* finally, edit **boilerLess-custom.less** file and place inside it all your custom style.


### Default index.html
This file must be the main html page of your project. Here you need to include the right css or less file.

```html
<link rel="stylesheet" href="css/normalize.css">
<link rel="stylesheet" href="css/boilerLess-globals.css">
<link rel="stylesheet" href="css/boilerLess-custom.css">
<link rel="stylesheet" href="css/boilerLess-utilities.css">
```

### From {less} to CSS
For a correct use of **boilerLess** you need to compile {less} files in common CSS files. There are many way to do this task such as a Grunt contrib or simply using a modern editor like Brakets. For this reason inside the boiler{LESS} package there are no tool for less compile. 


***


### Changes

#### Version 0.7.0 (first stable)

* New mixins added
* less/boilerLess.less and css/boilerLess.css removed
* Bootstrap CSS, JS and Fonts removed
* FontAwesome CSS and Fonts removed
* HTML5 Boilerplate updated to 5.2.0
* jQuery updated to 1.11.3
* Some CSS changes for print mediaquery
* Apache support updated

*This version is the release canditate for version 1.0.0*
