#Modern Site Boilerplate

###Made using
* HTML5 Boilerplate
* Gulp
* PHP

PHP suited my needs when putting this together but feel free to swap it out for whatever (ex. haml, jade). Note: You will need to alter the gulp file to accomodate changes related to which templating language, css preprocessor you decide to use.

*Disclaimer: This is in no way supposed to be the Starter Setup everybody should use for every project.  Just one of many that worked for me at the time.*

###Setup

Run
* `npm install`
* `gulp`

scss/js/images in the assets folder will be watched, then compiled/minified/autoprefixed and placed into the build folder.  Browsersync will start and open the browser at localhost:3000.  Changes to any file should trigger a live reload.

The main file loaded should be index.php.  The header.php and footer.php files are included within it contaning boilerplate code.

In order to use the 404.php file, you'll have to alter your .htaccess.

###Credits

* [HTML5 Boilerplate](https://html5boilerplate.com/)
* [Gulp](http://gulpjs.com/)
