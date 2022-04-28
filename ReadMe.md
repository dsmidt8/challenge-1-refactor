# Description

In this week's challenge I took a company's website and changed code to make it more organized and accessible, while maintaining it's layout and functionality. 

## Table of contents

```
*[URL](#URL)
*[Changes from Original Code made](#Changes from original code made)


## URL

```

## Criteria

```
GIVEN a webpage that meets accessibility standards

WHEN I view the source code
THEN I find semantic HTML elements

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning

WHEN I view the icon and image elements
THEN I find accessible alt attributes

WHEN I view the heading attributes
THEN I find that they fall in sequential order

WHEN I view the title element
THEN I find a concise, descriptive title
```

## Changes from original code made

HTML
* Line 11 and Line 26 - Section to header
* Line 12 remove span element to make "Horiseon" 1 word
* Line 14 and 26 - div to nav
* Line 29 - div to section
* line 81 and 86 - div to footer and removed footer class
* line 12 - removed header class
* line 34 and 56 - div to section
* line 37 - add id "search optimization" to div to give navigation a location to go to
* line 7 - changed title to "Horiseon SEO"
* Line 30 - title added to hero and labled team collaborating to describe image
* lines 38, 47, 56 - alts added with descriptioins of img elements
* lines 70, 79, 88 - emptyy alts to indicate unimportant images

CSS
* line 23 to 35 - remove .header h1 .SEO section, moved contents to header h1
* line 23, 33, 37 - header div to .header nav
* line 189 and 196 - .footer to footer
* line 11, 18, 25, 34, 37 - .header to header

- - -
© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
