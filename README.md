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
- Line 375: comment
- Line 450: new variable
- Lines 455-463: moved variables, added variable, refactored for-loop
- Lines 478-483: moved pizzasDiv variable outside for-loop
- Lines 508-527: separated scroll event from update function; added requestAnimationFrame
- Lines 530-533: modified updatePositions function with ticking
- Line 536: added a blank line for spacing
- Lines 538-539: new variable for calc removed from for-loop
- Lines 541-544: replaced variable contents with new variable
- Lines 558-559: reverted to original code
- Lines 565-566: reduced a value
- Lines 570-574: rollback of various values to original code

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

5. Optimizing Loading of the Google Font
https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/webfont-optimization?hl=en#optimizing-loading-and-rendering

*****
NEW 2/20/15 >> ADDED requestAnimationFrame
*****
1. Started with Piazza: https://piazza.com/class/i0sf6tsmg0r7do?cid=965
2. Reviewed CreativeJS > http://creativejs.com/resources/requestanimationframe/
3. Worked out solution through HTML5ROCKS example > http://www.html5rocks.com/en/tutorials/speed/rendering/#toc-vsync
4. Experimiented with > http://jsfiddle.net/wMkJg/

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
