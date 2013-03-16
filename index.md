---
layout: default
---

### How

WordPress-Gear is meant to be community driven, please feel free to jump in and add/remove any useful information via GitHub.

The easiest way to contribute is to have a GitHub account then click [index.md](https://github.com/wycks/WordPress-Gear/blob/gh-pages/index.md), then click edit. This will automatically fork this project to your account, make your changes then submit a pull request. There are additional instruction if you want to clone this locally in the readme.


### Contributors

Please refrain from submitting any commercial products or themes. Links
must allow for code browsing (github/bitbucket/svn..etc).


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
-   [WP-PowerShell](https://github.com/ericmann/WP-PowerShell) - Windows powershell for the WP-CLI
-   [VimPress](https://github.com/pentie/VimRepress/) - Post to WordPress from Vim

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
-   [Vim Syntax](https://github.com/kloppster/Wordpress-Vim-Syntax)
-   [Vim WordPress snippets](https://github.com/sudar/vim-wordpress-snippets)


`Misc` 

-   [WP-PhpTidy](https://github.com/scribu/wp-phptidy) - Format PHP code so that it conforms to the WordPress Coding Standards
-   [Nginx](https://github.com/perusio/wordpress-nginx) - Configuration for running WordPress
-   [WordPress-Skeleton](https://github.com/markjaquith/WordPress-Skeleton) - Basic layout of a WordPress Git repository
-   [WordPress Java](http://code.google.com/p/wordpress-java/) -  Java xmlrpc interface of WordPress
-   [WordPress-Coding-Standards](https://github.com/x-team/WordPress-Coding-Standards) -  PHP_CodeSniffer rules to enforce WordPress coding conventions


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
-   [WCM Current Admin Info](https://github.com/wecodemore/current-admin-info) - Info about current screen, contextual hooks & its globals
-   [WpDevTool](http://wordpress.org/extend/plugins/wpdevtool/) - Development tool for WordPress to track bugs, manage crons, permalinks and much more.

##### SQL debug

-   [MySQL Profiler](http://wordpress.org/extend/plugins/mysql-profiler/)
-   [SQL Monitor](http://wordpress.org/extend/plugins/sqlmon/)

##### Other

- [Console logger](https://github.com/MZAWeb/wp-log-in-browser) Log WP data to Chrome or Firefox

* * * * *

PHP Boilerplate
---------------

`PHP bits`

###### *Most of these are PHP classes*

##### Plugin stuff

-   [Plugin boilerplate](https://github.com/tommcfarlin/WordPress-Plugin-Boilerplate) - Organized, maintainable boilerplate for building plugins
-   [Object Oriented Plugin Template](https://github.com/convissor/oop-plugin-template-solution) - WordPress plugins using object-oriented programming practices
-   [Settings framework](https://github.com/gilbitron/WordPress-Settings-Framework) - A framework for the WordPress settings API
-   [scbFramework](http://wordpress.org/extend/plugins/scb-framework) - A set of useful classes for faster plugin development 
-   [WordPress Settings API](https://github.com/tareq1988/wordpress-settings-api-class) - Another WordPress settings API abstraction class 
-   [WP MVC](https://github.com/tombenner/wp-mvc) - MVC framework to create plugins
-   [DX-Plugin-Base](https://github.com/mpeshev/DX-Plugin-Base) - Base plugin for the WordPress system

##### Widgets

-   [Widget Boilerplate](https://github.com/tommcfarlin/WordPress-Widget-Boilerplate) - Maintainable boilerplate for building widgets
-   [Widget helper class](https://github.com/sksmatt/WordPress-Widgets-Helper-Class) - A class to ease creating Widgets

##### Updaters

-   [GitHub plugin update](https://github.com/jkudish/WordPress-GitHub-Plugin-Updater) - WordPress plugin updates via GitHub
-   [Update class](https://github.com/thomasgriffin/TGM-Updater) - Private and commercial plugin update class
-   [wp-plugin-in-github](https://github.com/sudar/wp-plugin-in-github) - Sync WordPress Plugins between Github and WordPress Plugin repository.

##### Custom fields (meta box)

-   [My-Meta-Box](https://github.com/bainternet/My-Meta-Box)
-   [Meta Box Plugin](https://github.com/rilwis/meta-box)
-   [Custom Metaboxes and Fields](https://github.com/jaredatch/Custom-Metaboxes-and-Fields-for-WordPress)
-   [WpAlchemy](https://github.com/farinspace/wpalchemy)
-   [Reusable WordPress Meta Boxes](https://github.com/tammyhart/Reusable-Custom-WordPress-Meta-Boxes)

Comparison of tools [CompareWP Content Type / Custom Fields](https://docs.google.com/spreadsheet/ccc?key=0AoY8IFUX301qdFhBaERLUEUwa3U0YjFYTnBmaU1mbmc#gid=3) 

##### Other

-   [SuperCPT](https://github.com/mboynes/super-cpt) CPT and meta box wrapper with icons
-   [Media Manager class](https://github.com/thomasgriffin/New-Media-Image-Uploader) - Integrating the new media manager work-flow into your plugins/themes
-   [WordPress Taxonomies Fields](https://github.com/bainternet/Tax-Meta-Class) - Class for creating WordPress taxonomies custom fields
-   [Pods framework](http://podsframework.org/) -  Expansive Framework  for custom content and fields
-   [WordPress transients interface](https://github.com/markjaquith/WP-TLC-Transients) - A WordPress transients interface
-   [Logging class](https://github.com/pippinsplugins/WP-Logging) - A a general logging system
-   [WP Session Manager](https://github.com/ericmann/wp-session-manager) - Session manager for WordPress
-   [WP CoffeeScript](http://wordpress.org/extend/plugins/wp-coffeescript/) - Use CoffeeScript in WordPress

* * * * *

Theme Stuff
---------------

##### Theme tools and boilerplate

-   [Prometheus](https://github.com/noeltock/prometheus) Front-end foundation (LESS, wpthumb)
-   [WordPress Template Base](https://github.com/wycks/WordPress-Template-Base) File structure based on TwentyEleven
