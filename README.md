## Udacity Front-end Nanodegree

This is my submission for project 5 of the Front-end Nanodegree, Website performance Optimization Project.


## My submission for this project:

1. index.html achieves a PageSpeed rank of over 90,
1. views/pizza.html scrolls at a minimum of 60fps,
1. The pizza size slider on views/pizza.html resize time is below 5ms.

### Edits made for index.html:

1. Inline Style.css,
1. Inline google fonts,
1. Async google-analytics.

### Edits made in views/pizza.html:

1. Inline Style.css.

### Edits made to views/js/main.js:

1. changePizzaSizes now alters to percentage width with additional variables defined outside for loop,
1. updatePositions no longer does a forced synchronous layout, with small edits changing querySelectorAll and caching items.length outside the for loop.
1.  Moving pizzas in background are reduced from 200 to 35, querySelectorAll is changed to getElementById and positions are updated through requestAnimationFrame.

The details of edits can be found in the comments for src/index.html, src/views/pizza.html and src/views/js/main.js.

The project is split into two files, src which consists of readable code with comments, and dist which includes minified files. Both include package.json and gulp.js.

### To run the project:

1. Git clone the project using the url https://github.com/JimRhead/frontend-nanodegree-mobile-portfolio.git,
1. Open folder labeled dist,
1. Open index.html using your browser of choice.

### To run the grunt.js task runner:

1. Ensure you have Node installed first. https://nodejs.org/en/download/,
1. After you have cloned this project, open your terminal and go to frontend-nanodegree-mobile-portfolio/src,
1. Run 'npm install'. This will install the grunt task runner based on the dependencies in package.json,
1. Run 'grunt'.
