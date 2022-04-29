# challenge-1-refactor


## Challenge
Refactor a website to fix bugs and make the code more accessible.

## Built With
* HTML
* CSS

## Criteria

GIVEN a webpage that meets accessibility standards:

* WHEN I view the source code
  THEN I find semantic HTML elements

* WHEN I view the structure of the HTML elements
  THEN I find that the elements follow a logical structure independent of styling and positioning

* WHEN I view the icon and image elements
  THEN I find accessible alt attributes

* WHEN I view the heading attributes
  THEN I find that they fall in sequential order

* WHEN I view the title element
  THEN I find a concise, descriptive title

## Changes Made

HTML:
* Line 11 and 26 - Section to Header
* Line 12 - Horiseon to 1 word by removing span
* Line 14 and 26 - div to nav
* Line 29 - div to section
* Line 81 and 86 - div to footer and removed class
* Line 12 - remove class=header
* Line 34 and 56 - div to section
* Line 37 - add id "Search engine optimization" to div to enable nav functionality
* Line 7 - Title to "horiseon SEO"
* Line 30 - title " team collaborating" added to hero for accessibility
* Line 38, 47, 56 - alts added w/ descriptions of img elements
* Line 70, 79, 88 - empty alts to indicate unimportant features

CSS:
* Line 23 - remove .header h1 .seo section, contents moved to .header h1
* Lines 25, 33, 37 - header div to .header nav
* Line 189 and 196 - .footer to footer
* Line 11, 18, 25, 34, 37 - .header to header

## Website
https://dsmidt8.github.io/challenge-1-refactor/


