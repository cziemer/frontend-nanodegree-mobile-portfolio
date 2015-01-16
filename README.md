# Udacity Mobile Portfolio Project

This project was ultimately completed utilizing Gulp. As a result, there are two folders:

 * Load the files inside _BUILD_ to view the optimized websites
 * Load the files indide _SRC_ to view original source coding

Optimized utilizing Gulp:

 * Optimized view - open from the BUILD folder
 * Moved style.css inline to main HTML files
 * Compressed all HTML, CSS, and JavaScript files
 * Removed render blocking JavaScript - Loaded JavaScript files async when applicable to improve page load time
 * Validated HTML, CSS and JavaScript
 * Minimized all images and saved locally

Steps Completed to Optimize this project (Main 3 HTML Files - Portfolio)

 * Corrected viewport code in HTML files
 * Closed divs on HTML files
 * Added JavaScript function to improve font loading
 * PageSpeed Insights scores: Mobile 91, Desktop 93/100 {unable to leverage browser caching or improve server response}

Steps Completed to Optimize this project (Pizza HTML and associated files)

 * Minimized jank in updatePositions by saving the scrollTop value instead of constantly recalculating it
 * Eliminated additional function calling by moving changeSliderLabel to inside existing function
 * Global variables added to store array lengths (no need to re-calculate)
 * Moved pizzasDiv variable out of for loop to eliminate re-calculating
 * Eliminated unnecessary arrays in main.js (same as default)
 * Changed querySelector to getElement statements to yield better results
 
### Invaluable sources used:

 * [Gulp](http://gulpjs.com/) for compression and validation
 * [This article](http://www.sitepoint.com/improve-page-performance-font-loader/) for improving Page Performance with a Font Loader
 * [This Jank demo site](https://www.igvita.com/slides/2012/devtools-tips-and-tricks/jank-demo.html) to provide a great way to cache data
 * [JPEG](http://jpeg-optimizer.com/), [CSS](http://cssminifier.com/), [JavaScript](http://jscompress.com/) compression before using GULP
 * [HTML](http://validator.w3.org/check), [CSS](http://jigsaw.w3.org/css-validator/), [JavaScript](http://www.jslint.com/) validators before using GULP
 * [GitHub Markdown Editor](http://jbt.github.io/markdown-editor/) to help with this readme