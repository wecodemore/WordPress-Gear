---
layout: default
---

### How

WordPress-Gear is meant to be community driven, please feel free to jump in and add/remove any useful information via [GitHub](https://github.com/wycks/WordPress-Gear).

The easiest way to contribute is to have a GitHub account then click [index.md](https://github.com/wycks/WordPress-Gear/blob/gh-pages/index.md), then click edit. This will automatically fork this project to your account so you can make changes, then submit a pull request. There are additional instruction if you want to clone this locally in the readme.


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


`Unit tests`

##### Unit Testing and profiling

-   [Trac SVN](http://unit-tests.svn.wordpress.org/trunk/)
-   [GitHub mirror](https://github.com/kurtpayne/wordpress-unit-tests)
-   [WordPress Handbook](http://make.wordpress.org/core/handbook/automated-testing/) - Guide to automated testing
-   [WP Mock](https://github.com/10up/wp_mock) - Unit tests using Mockery
-   [Theme XML sample data](https://wpcom-themes.svn.automattic.com/demo/theme-unit-test-data.xml) - Official sample data
-   [WP Test](http://wptest.io/) - Additional test/sample data


`Command line fu`

-   [WP-CLI](https://github.com/wp-cli/wp-cli) - The command-line tool for managing WordPress.
-   [WP-PowerShell](https://github.com/ericmann/WP-PowerShell) - Windows powershell for the WP-CLI
-   [VimPress](https://github.com/pentie/VimRepress/) - Post to WordPress from Vim
-   [SublPress](https://github.com/dnstbr/sublpress)  - Post to WordPress in Sublime
-   [wp-composer](https://github.com/srtfisher/wp-composer) - Adds Composer dependency management to plugins/themes via WP-CLI.

##### Build scripts

-   [WP Stack](https://github.com/markjaquith/WP-Stack) - Capistrano deploy
-   [Capistrano-WP](https://github.com/crowdfavorite/gem-capistrano-wp) - Alternative Capistrano deploy
-   [Wordmove](https://github.com/welaika/wordmove) - Rails gem
-   [Wp Project Tools](https://github.com/newsapps/wp-project-tools) - Fabric/Python CLI and automation
-   [WordPhing](https://github.com/wycks/WordPhing) - Phing/Php build script
-   [Yeoman-WordPress](https://github.com/romainberger/yeoman-wordpress) - Node, NPM and Ruby
-   [YeoPress](https://github.com/wesleytodd/YeoPress) - Yeoman
-   [Grunt-WP-Plugin](https://github.com/10up/grunt-wp-plugin) - Grunt (node)
-   [Wordpress-Heroku](https://github.com/mhoofman/wordpress-heroku) - Installing/running WordPress on Heroku
-   [Varying Vagrant](https://github.com/10up/varying-vagrant-vagrants) - Varying Vagrant Vagrants for WP
-   [Puppet WordPress](https://github.com/jonhadfield/puppet-wordpress) - Puppet
-   [Composerpress](https://github.com/Tarendai/composerpress) - Retroactively creates a composer.json for WP
-   [Grunt-WP-Deploy](https://github.com/stephenharris/grunt-wp-deploy) - Grunt to deploy a build directory to WordPress SVN
-   [Bedrock](https://github.com/roots/bedrock) - Gets you started with the best development tools,practices, and project structure


`IDE bundles`

##### WordPress snippets and auto-completions

-   [Sublime Text 2](https://github.com/purplefish32/sublime-text-2-wordpress)
-   [TextMate](https://github.com/Gipetto/wordpress.tmbundle)
-   [Aptana Studio](https://github.com/aptana/wordpress.ruble)
-   [Coda 2](https://github.com/deryckoe/WordPress-Syntax-Mode-for-Coda-2)
-   [Vim Syntax](https://github.com/kloppster/Wordpress-Vim-Syntax)
-   [Vim WordPress snippets](https://github.com/sudar/vim-wordpress-snippets)
-   [NetBeans WordPress plugin](https://github.com/junichi11/netbeans-wordpress-plugin/)
-   [Alfred v2 codex function reference](http://www.alfredforum.com/topic/2153-search-the-wordpress-function-reference/)
-   [Sublime Codex](https://github.com/welovewordpress/SublimeWordPressCodex) - Search the WordPress Codex inside Sublime


`Misc` 

-   [WP-PhpTidy](https://github.com/scribu/wp-phptidy) - Format PHP code so that it conforms to the WordPress Coding Standards
-   [Nginx](https://github.com/perusio/wordpress-nginx) - Configuration for running WordPress
-   [WordPress-Skeleton](https://github.com/markjaquith/WordPress-Skeleton) - Basic layout of a WordPress Git repository
-   [WordPress Java](http://code.google.com/p/wordpress-java/) -  Java xmlrpc interface of WordPress
-   [WordPress-Coding-Standards](https://github.com/x-team/WordPress-Coding-Standards) -  PHP CodeSniffer - enforce WordPress coding conventions
-   [WP.NET](http://wpdotnet.com/) - WordPress compiled to .NET, yes this exists.

* * * * *

Debug Tools
-----------

Plugins that help with debugging

##### Debug Bar and extensions

-   [Debug Bar](http://wordpress.org/plugins/debug-bar/) - Maintained by core devs
-   [Debug Bar Actions and Filters Addon](http://wordpress.org/plugins/debug-bar-actions-and-filters-addon/) - List of hooks( Actions + Filters )
-   [Debug Bar Action Hooks](http://wordpress.org/plugins/debug-bar-action-hooks/) - List fired hooks
-   [Debug Bar Console](http://wordpress.org/plugins/debug-bar-console/) - PHP/MySQL console to the debug bar
-   [Debug Bar Constants](http://wordpress.org/plugins/debug-bar-constants/) - List all WP and PHP constants
-   [Debug Bar Cron](http://wordpress.org/plugins/debug-bar-cron/) - Display scheduled events
-   [Debug Bar Extender](http://wordpress.org/plugins/debug-bar-extender/) - Adds profiler and extra tools
-   [Debug Bar List Script & Style Dependencies](http://wordpress.org/plugins/debug-bar-list-dependencies/) - Shows scripts/styles loaded for the current page & dependencies.
-   [Debug Bar Post Meta](http://wordpress.org/plugins/tdd-debug-bar-post-meta/) - Lists the post meta data for the current post 
-   [Debug Bar Post Types](http://wordpress.org/plugins/debug-bar-post-types/) - Detailed information about registered post types settings 
-   [Debug Bar Query Tracer](http://wordpress.org/plugins/debug-bar-query-tracer/) - Lets you trace what plugins are causing database queries
-   [Debug Bar Screen Info](http://wordpress.org/plugins/debug-bar-screen-info/) - Shows screen info of the current admin page
-   [Debug Bar Shortcodes](http://wordpress.org/plugins/debug-bar-shortcodes/) - Shows the registered shortcodes, any available information about them and where they are used
-   [Debug Bar Super Globals](http://wordpress.org/plugins/debug-bar-super-globals/) - Displays Super Global valiables for the current request
-   [Debug Bar Template Trace](https://github.com/Clorith/wordpress-debug-bar-template-trace) - Show which template files are loaded for a page
-   [Debug Bar Transients](http://wordpress.org/plugins/debug-bar-transients/) - Transient info
-   [PMC Benchmark](http://wordpress.org/plugins/pmc-benchmark/) - Benchmarking plugin to profile slow hooks

##### Debug plugins

-   [Core Control](http://wordpress.org/plugins/core-control/) - Lots of core options
-   [Query Monitor](https://github.com/johnbillion/QueryMonitor) - Monitor lots of debugging things
-   [Developer](http://wordpress.org/plugins/developer/installation/) - Quickly get setup
-   [Debug This](http://wordpress.org/plugins/debug-this/) - Lot of debug modes
-   [Debug Objects](http://wordpress.org/plugins/debug-objects/) - Lots of info
-   [Hook Sniffer](http://wordpress.org/plugins/wordpress-hook-sniffer/) - Action and filter sequence
-   [Depreciated Notices](http://wordpress.org/plugins/log-deprecated-notices/) - Log outdated functions
-   [Rewrite Analyzer](http://wordpress.org/plugins/monkeyman-rewrite-analyzer/) - Helps dreaded rewrites
-   [Rewrite Rules Inspector](http://wordpress.org/plugins/rewrite-rules-inspector/) - Straightforward WordPress admin tool for inspecting your rewrite rules
-   [BlackBox Debug Bar](http://wordpress.org/plugins/blackbox-debug-bar/) - Another debug bar
-   [User Switching](http://wordpress.org/plugins/user-switching/) - Instant switching between user accounts in WordPress.
-   [WCM Current Admin Info](https://github.com/wecodemore/current-admin-info) - Info about current screen, contextual hooks & its globals
-   [WpDevTool](http://wordpress.org/plugins/wpdevtool/) - Development tool for WP to track bugs, manage crons, permalinks, etc.
-   [WP-Pretty Debug](https://github.com/wycks/WP-Pretty-Debug) - Pretty var_dumps -links to queryposts.com API
-   [WP Crontrol](http://wordpress.org/plugins/crontrol/) - Lets you view and control what's happening in the WP-Cron system
-   [Kint Debugger](http://wordpress.org/plugins/kint-debugger/) - WordPress wrapper for Kint debugging tool. Integrates with the Debug Bar is present.

##### Profiling plugins

-   [Time-Stack](https://github.com/joehoyle/Time-Stack) - WordPress profiling
-   [P3 (Plugin Performance Profiler)](http://wordpress.org/plugins/p3-profiler/) - Test your plugins
-   [XHProf Profiler](http://wordpress.org/plugins/wp-xhprof-profiler/) - Profile plugins and themes using XHProf (Facebook)

##### SQL debug

-   [MySQL Profiler](http://wordpress.org/plugins/mysql-profiler/)
-   [SQL Monitor](http://wordpress.org/plugins/sqlmon/)

##### Other

- [Console Logger](https://github.com/MZAWeb/wp-log-in-browser) Log WP data to Chrome or Firefox
- [Wp-Debug-Toggle](https://github.com/matthewsimo/wp-debug-toggle) -  Toggle wp_debug via CLI

* * * * *

PHP Boilerplate
---------------

`PHP bits`

###### *Most of these are PHP classes*

##### Framework stuff

-   [Fields Framework](http://wordpress.org/plugins/fields-framework/) -  A framework which can be used by developers to add fields to various areas of the administration panel either manually or using the Visual Builder.
-   [Plugin Boilerplate](https://github.com/tommcfarlin/WordPress-Plugin-Boilerplate) - Organized, maintainable boilerplate for building plugins
-   [Object Oriented Plugin Template](https://github.com/convissor/oop-plugin-template-solution) - WordPress plugins using object-oriented programming practices
-   [Settings Framework](https://github.com/gilbitron/WordPress-Settings-Framework) - A framework for the WordPress settings API
-   [scbFramework](http://wordpress.org/plugins/scb-framework) - A set of useful classes for faster plugin development 
-   [WordPress Settings API](https://github.com/tareq1988/wordpress-settings-api-class) - Another WordPress settings API abstraction class 
-   [WP MVC](https://github.com/tombenner/wp-mvc) - MVC framework to create plugins
-   [DX-Plugin-Base](https://github.com/mpeshev/DX-Plugin-Base) - Base plugin for the WordPress system
-   [NHP Theme Options](https://github.com/leemason/NHP-Theme-Options-Framework) - Theme options framework
-   [Pods Framework](http://podsframework.org/) -  Expansive Framework  for custom content and fields
-   [Sanity Framework](https://github.com/Emerson/Sanity-Wordpress-Plugin-Framework) - OOP plugin framework
-   [Option Tree](https://github.com/valendesigns/option-tree) - UI Builder, Theme Options, and Meta Boxes
-   [Vafpress](http://vafpress.com/vafpress-framework/) - Admin toolbox framework
-   [Piklist](http://piklist.com/) - Powerful framework with lots of options
-   [WPX](https://bitbucket.org/alkah3st/wp-extend) - Make it easier to use WordPress as a CMS
-   [Wordpress Cuztom Helper](https://github.com/Gizburdt/Wordpress-Cuztom-Helper) -  Helper stuff for Devs

##### Widgets

-   [Widget Boilerplate](https://github.com/tommcfarlin/WordPress-Widget-Boilerplate) - Maintainable boilerplate for building widgets
-   [Widget Helper Class](https://github.com/sksmatt/WordPress-Widgets-Helper-Class) - A class to ease creating Widgets

##### Updaters

-   [GitHub Plugin Update](https://github.com/jkudish/WordPress-GitHub-Plugin-Updater) - WordPress plugin updates via GitHub
-   [Update Class](https://github.com/thomasgriffin/TGM-Updater) - Private and commercial plugin update class
-   [WP-Plugin-In-Github](https://github.com/sudar/wp-plugin-in-github) - Sync WordPress Plugins between Github and WordPress Plugin repository.
-   [External Update API](https://github.com/cftp/external-update-api) - Add support for updating themes and plugins via external sources instead of the WordPress.org repos

##### Other

-   [Media Manager Class](https://github.com/thomasgriffin/New-Media-Image-Uploader) - Integrating the new media manager work-flow into your plugins/themes
-   [WordPress Transients Interface](https://github.com/markjaquith/WP-TLC-Transients) - A WordPress transients interface
-   [Logging Class](https://github.com/pippinsplugins/WP-Logging) - A a general logging system
-   [WP Session Manager](https://github.com/ericmann/wp-session-manager) - Session manager for WordPress
-   [WP CoffeeScript](http://wordpress.org/plugins/wp-coffeescript/) - Use CoffeeScript in WordPress
-   [Dynamic Image Resize](https://github.com/franz-josef-kaiser/Dynamic-Image-Resize) - Resize images on the fly (like WPThumb/TimThumb but using PHP only)
-   [CleverRules](https://github.com/Giuseppe-Mazzapica/CleverRules) -  New way to handle rewrite rules
  

* * * * *

Meta Fields 
---------------

##### Meta data stuff (custom fields, meta fields, meta boxes, etc)

-   [My-Meta-Box](https://github.com/bainternet/My-Meta-Box) - Class for creating custom meta boxes
-   [Meta Box Plugin](https://github.com/rilwis/meta-box) - Easily create custom meta boxes
-   [Custom Metaboxes and Fields](https://github.com/WebDevStudios/Custom-Metaboxes-and-Fields-for-WordPress) - WebDevStudios 
-   [WpAlchemy](https://github.com/farinspace/wpalchemy) - Thin meta framework
-   [SuperCPT](https://github.com/mboynes/super-cpt) CPT and meta box wrapper with icons
-   [WordPress Taxonomies Fields](https://github.com/bainternet/Tax-Meta-Class) - WordPress taxonomies custom fields
-   [Automattic's Custom Metadata](https://github.com/Automattic/custom-metadata) - Add custom fields to your object types
-   [Custom Meta Boxes](https://github.com/humanmade/Custom-Meta-Boxes) - Humanmade's metaboxes with custom fields that will blow your mind
-   [Field Manager](http://fieldmanager.org/) - Fieldmanager is a toolkit for developers to create complex administration screen
-   [Sunrise](https://bitbucket.org/newclarity/sunrise-1) - New Clarity's Admin Post Forms & Fields
-   [Developers Custom Fields](https://github.com/gyrus/WordPress-Developers-Custom-Fields) - Tools for managing custom fields
-   [Simple Fields](https://github.com/bonny/WordPress-Simple-Fields)- Simple Fields

 
* * * * *

Theme Stuff
---------------

##### Theme tools and boilerplate

-   [Wordless](https://github.com/welaika/wordless) - Haml, Compass and Coffeescript (Ruby)
-   [Forge](https://github.com/thethemefoundry/forge) - Sass, LESS, and CoffeeScript (Ruby)
-   [Compass WordPress](https://github.com/pengwynn/compass-wordpress) - Sass
-   [Grunt-WP-Theme](https://github.com/10up/grunt-wp-theme) - Grunt Scaffold (node)
-   [Prometheus](https://github.com/noeltock/prometheus) Front-end foundation (LESS, wpthumb)
-   [WordPress Template Base](https://github.com/wycks/WordPress-Template-Base) File structure based on several themes and template hierarchy
-   [Theme-Check](http://wordpress.org/plugins/theme-check/) - Test your theme and make sure it's up to spec 
-   [Timber](http://github.com/jarednova/timber) - Write your theme using Twig templates (similar to Mustache, Handlebars, etc.)

If you are looking for theme option frameworks, look above under "Framework stuff".



