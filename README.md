# Project Structure

This is a brief explanation of how I thought we should plan to keep our project
structured and organized. Of course, feel free to change anything or we can 
discuss more on this when we meet if we need to change anything.

## Root Directory

1. README.md: This file. Initial explanation of the project structure, but will
plan on changing this file in the future for addressing our deliverables in 
one place.

2. index.html: The main entry point of our website. This is the homepage that 
users will land on when visiting the site. Thought it would be in the root 
directory rather than page for standard convention and ease of access (but,
really, it does not matter all that much). We can always rename this to
something else like home.html if people really want this to change.

## Folders

### 'assets'
This folder contains all the static assets for the website, including images, 
fonts, icons, etc. For styling later I propose, it would be a nice touch to 
import unique custom fonts and add a favicon.

### 'components'
This folder holds reusable HTML components, like the navigation bar 
(navbar.html), footer (footer.html), and other reusable components we may want
to use which can be included on multiple pages to ensure consistency.

### 'pages'
This folder contains all the individual HTML pages for the site (besides the 
main index.html).

### 'scripts'
All JavaScript files are stored here. JavaScript functions and logic for the
website are modularized into different files for easier maintenance. Some
examples include button logic, form validation, animations, and handling other
user interactions across different pages.

### 'styles'
Contains all the CSS files to style our website. We are keeping our styles 
organized by separating general/global styles and styles specific to individual 
components or pages. The global styles is located in styles/index.css.
