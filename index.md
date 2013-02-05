---
layout: default
---

Welcome
-------

WordPress-Gear is a compendium of useful *developer* tools for working
with WordPress.

[Base Tools](http://wycks.github.com/WordPress-Gear/#base-tools)  
[Debug Tools](http://wycks.github.com/WordPress-Gear/#debug-tools)  
[PHP Boilerplate](http://wycks.github.com/WordPress-Gear/#php-boilerplate)  

### How

WordPress-Gear is meant to be community driven, please feel free to jump
in and add/remove any useful information via GitHub.

To edit this project [fork](https://github.com/wycks/WordPress-Gear)
this project on GitHub and edit right in the GitHub UI or clone it locally,

    # how to clone locally
    $ git clone git://github.com/your_username/your_fork.git
    $ cd your_fork
    # switch branches to default github hosted pages
    $ git checkout -b gh-pages remotes/origin/gh-pages
    # Edit index.md 
    $ git push

Then send a pull request:
[GitHub-how-to](https://help.github.com/articles/using-pull-requests)

WordPress-Gears is written using [Jekyll](https://github.com/mojombo/jekyll), to make changes edit *index.md*.

### Contributors

Please refrain from submitting any commercial products or themes. Links
must allow for code browsing (github/bitbucket/svn..etc).

You can [@mention](https://github.com/blog/821) a GitHub username to
generate a link to their profile. The resulting `<a>` element will link
to the contributor's GitHub Profile.

* * * * *

Base Tools
----------

`WordPress`

##### Compressed format (.zip or .tar.gz)

-   [Latest Stable](http://wordpress.org/download/) - wordpress.org
-   [Nightly](http://wordpress.org/download/nightly/) - wordpress.org

##### Revision control - These builds roll the latest commits.

-   [SVN](http://core.svn.wordpress.org/) (Subversion)
-   [GitHub](https://github.com/WordPress/WordPress) (Git)
-   [BitBucket](https://bitbucket.org/Rarst/wordpress/overview) (Mercurial)


`Core Unit tests`

##### Core Testing and profiling via PHPUnit + official theme sample data

-   [Trac SVN](http://unit-tests.svn.wordpress.org/trunk/)
-   [GitHub mirror](https://github.com/kurtpayne/wordpress-unit-tests)
-   [Theme XML sample data](https://wpcom-themes.svn.automattic.com/demo/theme-unit-test-data.xml)


`Command line fu`

-   [WP-CLI](https://github.com/wp-cli/wp-cli) - The command-line tool for managing WordPress.

##### Build scripts

-   [WP Stack](https://github.com/markjaquith/WP-Stack) - Capistrano deploy
-   [Wordmove](https://github.com/welaika/wordmove) - Rails gem
-   [Wp Project Tools](https://github.com/welaika/wordmove) - Fabric/Python CLI and automation
-   [WordPhing](https://github.com/wycks/WordPhing) - Phing/Php build script
-   [Yeoman-WordPress](https://github.com/romainberger/yeoman-wordpress) - Node, NPM and Ruby

##### Theme scripts

-   [Wordless](https://github.com/welaika/wordless) - Haml, Compass and Coffeescript (Ruby)
-   [Forge](https://github.com/thethemefoundry/forge) - Sass, LESS, and CoffeeScript (Ruby)


`IDE bundles`

##### WordPress snippets and auto-completions

-   [Sublime Text 2](https://github.com/purplefish32/sublime-text-2-wordpress)
-   [TextMate](https://github.com/Gipetto/wordpress.tmbundle)
-   [Aptana Studio](https://github.com/aptana/wordpress.ruble)
-   [Coda 2](https://github.com/deryckoe/WordPress-Syntax-Mode-for-Coda-2)


`Misc` 

-   [WP-PhpTidy](https://github.com/scribu/wp-phptidy) - Format PHP code so that it conforms to the WordPress Coding Standards
-   [Nginx](https://github.com/perusio/wordpress-nginx) - Configuration for running WordPress
-   [WordPress-Skeleton](https://github.com/markjaquith/WordPress-Skeleton) - Basic layout of a WordPress Git repository
-   [WordPress Java](http://code.google.com/p/wordpress-java/) -  Java xmlrpc interface of WordPress


* * * * *

Debug Tools
-----------

Plugins that help with debugging

##### Debug Bar and extensions

-   [Debug Bar](http://wordpress.org/extend/plugins/debug-bar/) - Maintained by core devs
-   [Debug Bar Extender](http://wordpress.org/extend/plugins/debug-bar-extender/) - Adds profiler and extra tools
-   [Debug Bar Cron](http://wordpress.org/extend/plugins/debug-bar-cron/) - Display scheduled events
-   [Debug Bar Transients](http://wordpress.org/extend/plugins/debug-bar-transients/) - Transient info
-   [Debug Bar Template Trace](http://wordpress.org/extend/plugins/debug-bar-template-trace/) - Template load and order
-   [Debug Bar Action Hooks](http://wordpress.org/extend/plugins/debug-bar-action-hooks/) - List fired hooks
-   [Debug Bar Console](http://wordpress.org/extend/plugins/debug-bar-console/) - PHP/MySQL console to the debug bar

##### Debug plugins

-   [Core Control](http://wordpress.org/extend/plugins/core-control/) - Lots of core options
-   [Developer](http://wordpress.org/extend/plugins/developer/installation/) - Quickly get setup
-   [Debug This](http://wordpress.org/extend/plugins/debug-this/) - Lot of debug modes
-   [P3 (Plugin Performance Profiler)](http://wordpress.org/extend/plugins/p3-profiler/) - Test your plugins
-   [Debug Objects](http://wordpress.org/extend/plugins/debug-objects/) - Lots of info
-   [Hook Sniffer](http://wordpress.org/extend/plugins/wordpress-hook-sniffer/) - Action and filter sequence
-   [Depreciated Notices](http://wordpress.org/extend/plugins/log-deprecated-notices/) - Log outdated functions
-   [Rewrite Analyzer](http://wordpress.org/extend/plugins/monkeyman-rewrite-analyzer/) - Helps dreaded rewrites
-   [XHProf Profiler](http://wordpress.org/extend/plugins/wp-xhprof-profiler/) - Profile plug ins and themes using XHProf (Facebook)
-   [BlackBox Debug Bar](http://wordpress.org/extend/plugins/blackbox-debug-bar/) - Another debug bar

##### SQL debug

-   [MySQL Profiler](http://wordpress.org/extend/plugins/mysql-profiler/)
-   [SQL Monitor](http://wordpress.org/extend/plugins/sqlmon/)

* * * * *

PHP Boilerplate
---------------

`PHP bits`

###### *Most of these are PHP classes*

##### Plugin stuff

-   [Plugin boilerplate](https://github.com/tommcfarlin/WordPress-Plugin-Boilerplate) by @tommcfarlin
-   [Object Oriented Plugin Template](https://github.com/convissor/oop-plugin-template-solution)
-   [Settings framework](https://github.com/gilbitron/WordPress-Settings-Framework) by @gilbitron
-   [scbFramework](http://wordpress.org/extend/plugins/scb-framework/) - Classes for plugin dev
-   [WordPress Settings API](https://github.com/tareq1988/wordpress-settings-api-class) - by @tareq_cse
-   [WP MVC](https://github.com/tombenner/wp-mvc) - MVC framework to create plugins

##### Widgets

-   [Widget Boilerplate](https://github.com/tommcfarlin/WordPress-Widget-Boilerplate)
-   [Widget helper class](https://github.com/sksmatt/WordPress-Widgets-Helper-Class)

##### Updaters

-   [GitHub plugin update](https://github.com/jkudish/WordPress-GitHub-Plugin-Updater)
-   [Update class](https://github.com/thomasgriffin/TGM-Updater)

##### Custom fields (meta box)

-   [My-Meta-Box](https://github.com/bainternet/My-Meta-Box)
-   [Meta Box Plugin](https://github.com/rilwis/meta-box)
-   [Custom Metaboxes and Fields](https://github.com/jaredatch/Custom-Metaboxes-and-Fields-for-WordPress)
-   [WpAlchemy](https://github.com/farinspace/wpalchemy)
-   [Reusable WordPress Meta Boxes](https://github.com/tammyhart/Reusable-Custom-WordPress-Meta-Boxes)
-   [WordPress Taxonomies Fields](https://github.com/bainternet/Tax-Meta-Class)

##### Other

-   [Media Manager class](https://github.com/thomasgriffin/New-Media-Image-Uploader)
-   [Pods framework](http://podsframework.org/)
-   [WordPress transients interface](https://github.com/markjaquith/WP-TLC-Transients)
-   [Logging class](https://github.com/pippinsplugins/WP-Logging)
-   [WP Session Manager](https://github.com/ericmann/wp-session-manager)
-   [WP CoffeeScript](http://wordpress.org/extend/plugins/wp-coffeescript/)




