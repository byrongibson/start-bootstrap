Starter build system template for [HTML5Boilerplate][1] and [Bootstrap 3][2].  Build system built with [Grunt][3] and [Bower][4].

###Install

1.  clone repo
2.  `npm install`
3.  `bower install`
4.  customize site with the following source files:

    - `src/html/partials/*.html`
    - `src/styles/less/main.less`
    - `src/styles/less/theme.less`
    - `src/scripts/main.js`
    - `src/scripts/plugins.js`

5.  build unimified test version:
    `grunt test`
    `grunt connect:test`

6.  build minified production version:
    `grunt dist`
    `grunt connect:dist`

7.  build minified and gziped production version:
    `grunt gzip`
    `grunt connect:dist`

[1]:http://html5boilerplate.com/
[2]:http://getbootstrap.com/
[3]:http://gruntjs.com/
[4]:http://bower.io/
