Grunt Kickstart
===============

A basic configuration for Grunt with SASS, Compass and LiveReload.

It's used mostly for [bootstrap-sass](https://github.com/twbs/bootstrap-sass) projects and [Drupal](https://www.drupal.org/) themes.

###How to use

1. Install [Ruby] (https://www.ruby-lang.org/en/installation/) and [node.js] (http://nodejs.org/)

2. Install necessary gems: ```gem install bootstrap-sass compass```

3. Install necessary node.js packages (package.json): ```npm install```

4. Install and enable [LiveReload browser plugin](http://feedback.livereload.com/knowledgebase/articles/86242-how-do-i-install-and-use-the-browser-extensions-)

5. Start watching for changes (Gruntfile.js): ```grunt```  
Any changes in scss will cause their recompilation.
Any changes in scss and PHP templates will cause page reload.

## Examples of use

A similar approach is used in [Designless Drupal theme](https://github.com/konstantin-komelin/designless)
