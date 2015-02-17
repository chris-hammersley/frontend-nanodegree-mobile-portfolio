Project 4 - Chris Hammersley
============================
View Optimized Site Here --> http://chris-hammersley.github.io/frontend-nanodegree-mobile-portfolio/
============================
I refactored the following files & lines of code. Details in the comments.
==========
index.html
==========
- moved Google Font load to CSS
- added a media type to print css
- added async to perfmatter.js
- modified portfolio copy
- optimized hosted images
- added attribute tags to external images

=================
/views/ja/main.js
=================
- Line 450: new variable
- Line 455: moved dx variable
- Line 457: moved newwidth variable
- Line 459: new variable
- Line 461: refactor for loop with new variable
- Line 479: moved pizzaDiv variable
- Line 513: new variable for scrollTop value
- Line 536: reduced number of pizzas

==============
RESOURCES USED
==============
I used the following resources for additional help, information & inspiration!
***********
NEW 2/16/15 >> INLINED MY CRITICAL CSS
***********
I used a combination of the following to identify above-the-fold rendering CSS and then inline it while sideloading the remaining CSS files

1. Determining What's Critical Above the Fold
http://css-tricks.com/authoring-critical-fold-css/

2. Javascript to use for a Bookmarklet
https://gist.github.com/PaulKinlan/6284142

3. The Bookmarkleter Tool (open Console to see result)
http://chriszarate.github.io/bookmarkleter/

4. loadCSS Async
https://github.com/filamentgroup/loadCSS

===
WEB
===
Understanding User Timing
http://www.html5rocks.com/en/tutorials/webperformance/usertiming/

Learning about Jank Free Video
http://jankfree.org/
http://addyosmani.com/blog/making-a-site-jank-free/

Scrolling Speed
http://www.html5rocks.com/en/tutorials/speed/scrolling/

Getting Down & Dirty with Chrome Timeline & Performance Profiling
https://developer.chrome.com/devtools/docs/timeline

requestAnimationFrame
http://www.html5rocks.com/en/tutorials/speed/rendering/#toc-vsync
http://creativejs.com/resources/requestanimationframe/

Add Google Fonts to CSS instead of HTML (for testing the speed gain/loss)
http://stackoverflow.com/questions/14676613/how-to-import-google-web-font-in-css-file

Translate // Didn't end up using
http://www.paulirish.com/2012/why-moving-elements-with-translate-is-better-than-posabs-topleft/

======
PIAZZA
======
Tools & sites to help understand & identify FPS scrolling issues
https://piazza.com/class/i0sf6tsmg0r7do?cid=729
https://piazza.com/class/i0sf6tsmg0r7do?cid=825
https://piazza.com/class/i0sf6tsmg0r7do?cid=761
https://piazza.com/class/i0sf6tsmg0r7do?cid=1198

Optimizing Google Fonts & CSS
https://piazza.com/class/i0sf6tsmg0r7do?cid=743
https://piazza.com/class/i0sf6tsmg0r7do?cid=1019
https://piazza.com/class/i0sf6tsmg0r7do?cid=1031
