# Kilovolt Blog - Lab 03 

**Author**: Carl Olson and Patricia Raferty
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
This is a practice project. The purpose of it is to create a fun website containing a blog with icons that are appealing to the user, and have the page be responsive so that it looks as desired on both desktop and mobile screens. The main problem domain has to do with the responsive design of this website. We want to be able to filter content by author or category, and have the menu items show the appropriate content, all on a single page. 


## Getting Started

The user would need to 
* Create index.html
* Get the icons from IcoMoon
* Get the normalize.css from github.com/necolas/normalize.css
* Search and find images of bacon, baseball, and cats
* Add filler text
* Build CSS files according to SMACSS methodology
* Include link to jQuery library (CDN)
* Create the articles as objects within an array with consistent property values
* Create a constructor function to make the article array accessible to the constructor's method
* Use jQuery to access and clone HTML elements of the DOM and populate those elements with content from the article array
* Create forEach loops to generate new object instances and then append them to the DOM

## Architecture

We used html, css, markdown, and JavaScript. This application is a blog of various ipsums. This application is design with mobile first in mind, and extra css code for desktop viewers, with a breakpoint at 640px. The mobile viewers, to maximize screen space, start with the dropdown menu hidden, and the menu becomes visible when the hamburger icon is hovered over. The desktop viewers do not see the hamburger icon, and can see the nav menu from the beginning.

## Change Log

02-14-2018 9:00am - Forked and cloned.
02-14-2018 10:00am - Finished populate filters and author filter functions.
02-14-2018 12:00pm - Finished category filter function and handleMainNav function.
02-14-2018 1:00pm - Updated readme and userstories. 

## Credits and Collaborations

* Thanks to our instructors, classmates, and TAs. 
* We referenced the jQuery cheat sheet: https://oscarotero.com/jquery/
* We used a normalize.css file found here: github.com/necolas/normalize.css