![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67) Lab 02: jQuery and the DOM
===

## Code Wars Challenge

Complete [today's Kata](https://www.codewars.com/kata/my-head-is-at-the-wrong-end) and follow the submission instructions from Lab 01.

## Lab 02 Submission Instructions
Follow the submission instructions from Lab 01.

## Resources  
[jQuery cheatsheet](https://oscarotero.com/jquery/)

## Configuration
_Your repository must include:_

```
02-jquery-and-the-dom
└── starter-code
└── driver-navigator
  ├── .eslintrc.json
  ├── .gitignore
  ├── LICENSE
  ├── index.html
  ├── scripts
  │   ├── article.js
  │   └── blogArticles.js
  ├── styles
  │   ├── base.css
  │   ├── layout.css
  │   └── modules.css
  └── vendor
      └── styles
          ├── fonts
          │   ├── icomoon.eot
          │   ├── icomoon.svg
          │   ├── icomoon.ttf
          │   └── icomoon.woff
          ├── icons.css
          └── normalize.css
  └── PULL_REQUEST_TEMPLATE.md
  └── README.md
```

## User Stories and Feature Tasks

- Continue styling the app using SMACSS practices. Take a few minutes for code review of your partner's CSS and decide how to incorporate it into your paired lab. You can choose one partner's CSS structure, or you can combine them as you see fit. Seek to optimize and organize your CSS as much as possible!

*As a user, I want my site to display my blog articles in a clear, logical way so that I can find the most recent articles first and the blog is easy to read.*

- Complete the `toHtml()` method, which will ultimately be used to render each article instance to the DOM.
- The articles should be sorted by date.

*As a developer, I want to make my code DRY and render articles from a separate data file so that my HTML file is not cluttered with lengthy and repetitive code.*

- Complete the `Article()` constructor and create instances by assigning all of the properties of each data object to properties of `this`.

*As a developer, I want to utilize the jQuery library's functionality so that I can efficiently access, traverse, and manipulate elements on the DOM.*

- Add the necessary script tag to include jQuery in the app.
- Utilize jQuery functionality to modify the display property of DOM elements.
- Utilize jQuery functionality to traverse the DOM and complete the HTML template for the articles.

*As a developer, I want to optimize iteration with JavaScript array methods so that my code is more condensed and maintainable.*

- Refactor all `for` loops using the `.forEach()` method.


## Documentation
_Your README.md must include:_

```md
# Code 301 Lab 02 - Adding articles to the blog.

**Author**: Daniel / Candice
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
We are taking a list of articles and appending them to an HTML document on the fly. If this application were attached to a database, it would continue to add each newly published article
as they were created.

## Getting Started
You would need to clone our repo, make sure you had live-server installed, and then access the index.html file. Simple!

## Architecture
jQuery, CSS, HTML. Using an array and a constructor to create new articles. 

## Change Log
Author: Candice 'canned-ice' Thomas <candicebthomas@gmail.com>
Date: Wed Aug 15 12:33:57 2018 -0700 - replaced for loops with forEach

Author: Candice 'canned-ice' Thomas <candicebthomas@gmail.com>
Date: Wed Aug 15 11:12:47 2018 -070 - added jquery traversal of article

Author: Daniel Frey <dann.frey@me.com>
Date: Wed Aug 15 10:39:39 2018 -0700 - updated the PRT, and fixed object constructor

Author: Daniel Frey <dann.frey@me.com>
Date: Wed Aug 15 10:21:01 2018 -0700 - more css changes

Author: Daniel Frey <dann.frey@me.com>
Date: Wed Aug 15 10:13:58 2018 -0700 - started on js

Author: Daniel Frey <dann.frey@me.com>
Date: Wed Aug 15 09:55:14 2018 -0700 - added css classes

Author: Daniel Frey <dann.frey@me.com>
Date: Wed Aug 15 09:49:27 2018 -0700 - added css

Author: Daniel Frey <dann.frey@me.com>
Date: Wed Aug 15 08:42:54 2018 -0700 - created folder

## Credits and Collaborations
Thank you to Koko and John for all of their help in resolving our infinite loop.
-->
```
