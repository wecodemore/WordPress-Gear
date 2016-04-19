---
layout: default
---

### How

WordPress-Gear is meant to be community driven, please feel free to jump in and add/remove any useful information via [GitHub](https://github.com/wycks/WordPress-Gear).

The easiest way to contribute is to have a GitHub account then click [index.md](https://github.com/wycks/WordPress-Gear/blob/gh-pages/index.md), then click edit. This will automatically fork this project to your account so you can make changes, then submit a pull request. There are additional instruction if you want to clone this locally in the readme.


### Contributors

Please refrain from submitting any commercial products or themes. Links
must allow for code browsing (github/bitbucket/svn..etc).

I will now be posting updates to this page via my twitter account: [https://twitter.com/wycks_s](https://twitter.com/wycks_s)


* * * * *

Base Tools
----------

`WordPress`

##### Compressed format (.zip or .tar.gz)

-   [Latest Stable](http://wordpress.org/download/) - wordpress.org
-   [Nightly](http://wordpress.org/download/nightly/) - wordpress.org

##### Revision control (core) - These builds roll the latest commits.

-   [SVN](http://core.svn.wordpress.org/) (Subversion)
-   [Git](git://core.git.wordpress.org/) (Git)
-   [GitHub](https://github.com/WordPress/WordPress) (Git)

##### Revision control (trunk) - These repos contain source code, tools, and tests.

-   [SVN](http://develop.svn.wordpress.org/trunk/) (Subversion)
-   [Git](git://develop.git.wordpress.org/) (Git)


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
-   [WP-CLI GUI](http://wpcligui.com/) - A GUI for the command line interface for WordPress.
-   [EasyEngine](https://github.com/rtCamp/easyengine/) - Python tool to easily manage your WordPress websites with NGINX webserver - supported on Ubuntu and Debian Linux.
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
-   [Varying Vagrant](https://github.com/Varying-Vagrant-Vagrants/VVV) - Varying Vagrant Vagrants for WP
-   [VCCW](https://github.com/miya0001/vagrant-chef-centos-wordpress) - Vagrant designed for development of WordPress plugins, themes, or websites
-   [Puppet WordPress](https://github.com/jonhadfield/puppet-wordpress) - Puppet
-   [Composerpress](https://github.com/Tarendai/composerpress) - Retroactively creates a composer.json for WP
-   [Grunt-WP-Deploy](https://github.com/stephenharris/grunt-wp-deploy) - Grunt to deploy a build directory to WordPress SVN
-   [Bedrock](https://github.com/roots/bedrock) - Gets you started with the best development tools,practices, and project structure
-   [WPacked](https://github.com/enricodeleo/wpacked) - A development starter kit with portability and immediate deployment in mind
-   [wp-scratch-box](https://github.com/apleasantview/wp-scratch-box) - A Vagrant config for WP trainings, workshops, staging environments, ...


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
-	[PHPStorm integration](https://github.com/x-team/wp-phpstorm)
-	[PHPStorm code style](https://github.com/Automattic/PhpStorm-Resources)
-	  [Brackets](https://github.com/Tusko/brackets-wp-hint/)


`Code sniffers & fixing`

-   [WordPress Coding Standards Handbook](https://make.wordpress.org/core/handbook/best-practices/coding-standards/) - The official CSS, HTML, JS and PHP coding standards for WordPress.
-   [WordPress-Coding-Standards](https://github.com/WordPress-Coding-Standards/WordPress-Coding-Standards) -  PHP CodeSniffer - enforce WordPress coding conventions.
-   [WP-PhpTidy](https://github.com/scribu/wp-phptidy) - Format PHP code so that it conforms to the WordPress Coding Standards.
-   [PHPCompatibility](https://github.com/wimg/PHPCompatibility) - PHP CodeSniffer to test your code for PHP cross-version compatibility so you can catch those non-PHP 5.2 compatible syntaxes early.
-   [JSHint Config](https://develop.svn.wordpress.org/trunk/.jshintrc) - The official JS hint configuration.


`Misc`

-   [Nginx](https://github.com/perusio/wordpress-nginx) - Configuration for running WordPress
-   [WordPress-Skeleton](https://github.com/markjaquith/WordPress-Skeleton) - Basic layout of a WordPress Git repository
-   [WordPress Java](http://code.google.com/p/wordpress-java/) -  Java xmlrpc interface of WordPress
-   [WP.NET](http://wpdotnet.com/) - WordPress compiled to .NET, yes this exists.
-   [WordPress Packagist](http://wpackagist.org/) - Mirror of the wp.org theme and plugin repositories for use with Composer.
-   [Database Search & Replace script](https://github.com/interconnectit/Search-Replace-DB) - Easily search & replace data in a WP database. Fully supports handling of serialized strings. Especially useful when migrating a site to another domain/from test to production. [Full docs](https://interconnectit.com/products/search-and-replace-for-wordpress-databases/).

* * * * *

Debug Tools
-----------

Plugins that help with debugging

##### Debug Bar

-   [Debug Bar](http://wordpress.org/plugins/debug-bar/) - Maintained by core devs.
-   [Debug Bar Toggle](https://wordpress.org/plugins/debug-bar-toggle/) - (Temporarily) Enable and disable the Debug Bar with a keystroke: ctrl + d.

###### Debug Bar extensions

-   [Debug Bar Actions and Filters Addon](http://wordpress.org/plugins/debug-bar-actions-and-filters-addon/) - List of action hooks firec for the curent request and list all callbacks hooked into actions and filters ).
-   [Debug Bar Action Hooks](http://wordpress.org/plugins/debug-bar-action-hooks/) - List fired hooks.
-   [Debug Bar Console](http://wordpress.org/plugins/debug-bar-console/) - PHP/MySQL console to the debug bar.
-   [Debug Bar Constants](http://wordpress.org/plugins/debug-bar-constants/) - List all WP and PHP constants.
-   [Debug Bar Cron](http://wordpress.org/plugins/debug-bar-cron/) - Display scheduled events.
-   [Debug Bar Custom Info](https://wordpress.org/plugins/debug-bar-custom-info/) - Output custom debug info just like `console.log`.
-   [Debug Bar Extender](http://wordpress.org/plugins/debug-bar-extender/) - Adds profiler and extra tools.
-   [Debug Bar List Script & Style Dependencies](http://wordpress.org/plugins/debug-bar-list-dependencies/) - Shows scripts/styles loaded for the current page & dependencies.
-   [Debug Bar Localization](https://wordpress.org/plugins/debug-bar-localization/) - Shows information about the locale of the WP install, the language files loaded and missing `load_..._textdomain()` calls.
-   [Debug Bar Post Meta](http://wordpress.org/plugins/tdd-debug-bar-post-meta/) - Lists the post meta data for the current post.
-   [Debug Bar Post Types](http://wordpress.org/plugins/debug-bar-post-types/) - Detailed information about registered post types settings.
-   [Debug Bar Query Count Alert](https://wordpress.org/plugins/debug-bar-query-count-alert/) - Replace the Debug Bar button text with the database query count and time.
-   [Debug Bar Query Tracer](http://wordpress.org/plugins/debug-bar-query-tracer/) - Lets you trace what plugins are causing database queries.
-   [Debug Bar Remote Requests](https://wordpress.org/plugins/debug-bar-remote-requests/) - Log and profile remote requests made through the HTTP API.
-   [Debug Bar Rewrite Rules](https://wordpress.org/plugins/fg-debug-bar-rewrite-rules/) - Displays the current rewrite rules for the site.
-   [Debug Bar Roles and Capabilities](https://wordpress.org/plugins/debug-bar-roles-and-capabilities/) - Shows all WP User roles and associated capabilities.
-   [Debug Bar Screen Info](http://wordpress.org/plugins/debug-bar-screen-info/) - Shows screen info of the current admin page.
-   [Debug Bar Shortcodes](http://wordpress.org/plugins/debug-bar-shortcodes/) - Shows the registered shortcodes, any available information about them and where they are used.
-   [Debug Bar Sidebars & Widgets](https://wordpress.org/plugins/debug-bar-sidebars-widgets/) - Shows information about the sidebars and widgets on the current page. Integrates with [Content Aware Sidebars](https://wordpress.org/plugins/content-aware-sidebars/) plugin.
-   [Debug Bar Slow Actions](https://wordpress.org/plugins/debug-bar-slow-actions/) - Lists the top 100 slowest actions and filters during a page request in WordPress.
-   [Debug Bar Super Globals](http://wordpress.org/plugins/debug-bar-super-globals/) - Displays Super Global variables for the current request.
-   [Debug Bar Template Trace](https://github.com/Clorith/wordpress-debug-bar-template-trace) - Show which template files are loaded for a page.
-   [Debug Bar Transients](http://wordpress.org/plugins/debug-bar-transients/) - Transient info.
-   [Debug My Plugin with Debug Bar](https://wordpress.org/plugins/debug-my-plugin/) - A simple way to add your own personal debugging output to Debug Bar.
-   [PMC Benchmark](http://wordpress.org/plugins/pmc-benchmark/) - Benchmarking plugin to profile slow hooks.
-   [What Scripts Styles Debug Bar](https://wordpress.org/plugins/scripts-styles-debug-bar/) - Display all enqueued scripts and styles.

###### Debug Bar plugin specific extensions

-   [Debug Bar bbPress](https://wordpress.org/plugins/debug-bar-bbpress/) - Displays information about the bbPress runtime.
-   [Debug Bar Easy Digital Downloads](https://github.com/easydigitaldownloads/debug-bar-edd) - Displays information of the EDD Cart and EDD Sessions.
-   [WooCommerce Debug Bar](https://wordpress.org/plugins/woocommerce-debug-bar/) - Adds a WooCommerce debug panel.


##### Query Monitor and extensions

-   [Query Monitor](https://github.com/johnbillion/query-monitor) - A WordPress plugin for monitoring database queries, hooks, conditionals, HTTP requests, query vars, environment, redirects, and more.
-   [Query Monitor bbPress & BuddyPress Conditionals](https://wordpress.org/plugins/query-monitor-bbpress-buddypress-conditionals/) - Adds bbPress & BuddyPress functions to the Conditionals panel.
-   [Query Monitor Checking Variable](https://wordpress.org/plugins/query-monitor-extension-checking-variables/) - Check the value of variables in your code. Outputs to Query Monitor or to the browser console.
-   [Query Monitor Extend](https://github.com/crstauf/query-monitor-extend) - Lists conditionals for WooCommerce, plus many core constants and paths.
-   [Query Monitor Flamegraph](https://github.com/humanmade/query-monitor-flamegraph) - Add profiling framegraphs to Query Monitor. Requires the [forp](http://anthonyterrien.com/forp/) PHP extension.
-   [Query Monitor Included Files](https://github.com/khromov/wp-query-monitor-included-files) - Shows the included files for each page load, along with their component and file size.
-   [Query Monitor Sage Template](https://github.com/khromov/wp-query-monitor-sage-template) - Shows the active [Sage](https://roots.io/sage/) template in use.

Query Monitor also transparently supports all [Debug Bar](http://wpgear.org/#debug-bar-extensions) add-on plugins.


##### Debug plugins

-   [Core Control](http://wordpress.org/plugins/core-control/) - Lots of core options
-   [Developer](http://wordpress.org/plugins/developer/) - Quickly get setup
-   [Debug This](http://wordpress.org/plugins/debug-this/) - Lot of debug modes
-   [Debug Objects](http://wordpress.org/plugins/debug-objects/) - Lots of info
-   [Hook Sniffer](https://wordpress.org/plugins/hook-sniffer/) - Action and filter sequence
-   [Log Deprecated Notices](http://wordpress.org/plugins/log-deprecated-notices/) - Log outdated functions
-   [Log Deprecated Notices Extender](https://wordpress.org/plugins/log-deprecated-notices-extender/) - Show deprecated notices in the admin toolbar.
-   [Rewrite Analyzer](http://wordpress.org/plugins/monkeyman-rewrite-analyzer/) - Helps dreaded rewrites
-   [Rewrite Rules Inspector](http://wordpress.org/plugins/rewrite-rules-inspector/) - Straightforward WordPress admin tool for inspecting your rewrite rules
-   [Rewrite Rule Testing](https://github.com/alleyinteractive/rewrite-testing) - Unit test your rewrite rules from the WordPress Admin
-   [BlackBox Debug Bar](http://wordpress.org/plugins/blackbox-debug-bar/) - Another debug bar
-   [User Switching](http://wordpress.org/plugins/user-switching/) - Instant switching between user accounts in WordPress.
-   [WCM Current Admin Info](https://github.com/wecodemore/current-admin-info) - Info about current screen, contextual hooks & its globals
-   [WpDevTool](http://wordpress.org/plugins/wpdevtool/) - Development tool for WP to track bugs, manage crons, permalinks, etc.
-   [WP-Pretty Debug](https://github.com/wycks/WP-Pretty-Debug) - Pretty var_dumps -links to queryposts.com API
-   [WP Crontrol](http://wordpress.org/plugins/wp-crontrol/) - Lets you view and control what's happening in the WP-Cron system
-   [Kint Debugger](http://wordpress.org/plugins/kint-debugger/) - WordPress wrapper for Kint debugging tool. Integrates with the Debug Bar is present.
-   [WP PHP Console](https://github.com/nekojira/wp-php-console) - Debug WordPress from Chrome Dev Tools console and run your PHP code live from a browser terminal.
-   [Option Inspector](https://wordpress.org/plugins/options-inspector/) - Inspect and edit options, even serialized ones. 

##### Profiling plugins

-   [Time-Stack](https://github.com/joehoyle/Time-Stack) - WordPress profiling
-   [P3 (Plugin Performance Profiler)](http://wordpress.org/plugins/p3-profiler/) - Test your plugins
-   [XHProf Profiler](http://wordpress.org/plugins/wp-xhprof-profiler/) - Profile plugins and themes using XHProf (Facebook)
-   [Laps](https://github.com/Rarst/laps) - Light-weight profiling plugin
-   [What's running](https://wordpress.org/plugins/whats-running/) - Lists all files which were loaded (included/required) for the current page request, with file size indicator, in the page footer.

##### SQL debug

-   [MySQL Profiler](http://wordpress.org/plugins/mysql-profiler/)
-   [SQL Monitor](http://wordpress.org/plugins/sqlmon/)

##### Other

-   [Console Logger](https://github.com/MZAWeb/wp-log-in-browser) Log WP data to Chrome or Firefox
-   [Wp-Debug-Toggle](https://github.com/matthewsimo/wp-debug-toggle) -  Toggle wp_debug via CLI
-   [Demo Data Creator](https://wordpress.org/plugins/demo-data-creator/) - Easily fill a test install with data to test with. Can create demo users, blogs, posts, comments and more.


* * * * *

PHP Boilerplate
---------------

`PHP bits`

###### *Most of these are PHP classes*

##### Framework stuff

-   [Fields Framework](https://wordpress.org/plugins/fields-framework/) -  A framework which can be used by developers to add fields to various areas of the administration panel either manually or using the Visual Builder. 
-   [Plugin Boilerplate](https://github.com/DevinVinson/WordPress-Plugin-Boilerplate) / [WPPB.io](http://wppb.io/) / - Organized, maintainable boilerplate for building plugins
-   [Object Oriented Plugin Template](https://github.com/convissor/oop-plugin-template-solution) - WordPress plugins using object-oriented programming practices 
-   [Settings Framework](https://github.com/jamesckemp/WordPress-Settings-Framework) - A framework for the WordPress settings API
-   [scbFramework](https://wordpress.org/plugins/scb-framework/) - A set of useful classes for faster plugin development 
-   [WordPress Settings API](https://github.com/tareq1988/wordpress-settings-api-class) - Another WordPress settings API abstraction class 
-   [WP MVC](https://github.com/tombenner/wp-mvc) - MVC framework to create plugins
-   [Themosis MVC Framework](http://framework.themosis.com/) - MVC theme development framework, inspired by Laravel
-   [DX-Plugin-Base](https://github.com/mpeshev/DX-Plugin-Base) - Base plugin for the WordPress system
-   [Redux Framework](https://github.com/ReduxFramework/ReduxFramework) - Theme options framework
-   [Kirki Toolkit](https://github.com/aristath/kirki) - Theme Options framework using the Customizer
-   [Pods Framework](http://pods.io/) -  Expansive Framework  for custom content and fields
-   [Sanity Framework](https://github.com/Emerson/Sanity-Wordpress-Plugin-Framework) - OOP plugin framework 
-   [Option Tree](https://github.com/valendesigns/option-tree) - UI Builder, Theme Options, and Meta Boxes
-   [Vafpress](http://vafpress.com/vafpress-framework/) - Admin toolbox framework
-   [Piklist](https://piklist.com/) - Powerful framework with lots of options
-   [Wordpress Cuztom Helper](https://github.com/gizburdt/cuztom) -  Quickly register Custom Post Types, Taxonomies, Meta Boxes, Menu Pages and Sidebars
-   [WordPress Plugin Framework](https://github.com/theantichris/WordPress-Plugin-Boilerplate) - OOP framework for quickly building WordPress plugins 
-   [WPDK - Wordpress Developer Kit](http://wpxtreme.github.io/wpdk/) - OOP MVC Framework with over 150 new classes and more then 3500 methods to build your plugins
-   [WordPress Plugin Template](https://github.com/hlashbrooke/WordPress-Plugin-Template) - A robust code template for creating a standards-compliant WordPress plugin.
-   [WordPress Plugin Boilerplate Powered](https://github.com/Mte90/WordPress-Plugin-Boilerplate-Powered) - The WordPress Plugin Boilerplate Powered is a complete foundation (without framework with many independent libraries) for building your WordPress plugins. Yeoman Generator available and Grunt & Sass support.

##### Widgets

-   [Widget Boilerplate](https://github.com/tommcfarlin/WordPress-Widget-Boilerplate) - Maintainable boilerplate for building widgets
-   [Widget Helper Class](https://github.com/sksmatt/WordPress-Widgets-Helper-Class) - A class to ease creating Widgets

##### Updaters

-   [Github Updater](https://github.com/afragen/github-updater) - WordPress plugin / theme updates via GitHub (and GitHub Enterprise), GitLab
-   [GitHub Plugin Update](https://github.com/jkudish/WordPress-GitHub-Plugin-Updater) - WordPress plugin updates via GitHub
-   [Update Class](https://github.com/thomasgriffin/TGM-Updater) - Private and commercial plugin update class
-   [WP-Plugin-In-Github](https://github.com/sudar/wp-plugin-in-github) - Sync WordPress Plugins between Github and WordPress Plugin repository.
-   [External Update API](https://github.com/cftp/external-update-api) - Add support for updating themes and plugins via external sources instead of the WordPress.org repos
-   [Plugin Update Checker](https://github.com/YahnisElsts/plugin-update-checker) - Add support for updating externally hosted plugins via the normal WP update flow. Easiest to be used in combination with [WP Update Server](https://github.com/YahnisElsts/wp-update-server) which will provide API responses for those plugins similar to the WP.org API expected responses.

##### Other

-   [GenerateWP](https://generatewp.com/) - Generate the code for adding taxonomies, post types, sidebars, menus, shortcodes, queries, cron jobs and much more.
-   [Media Manager Class](https://github.com/thomasgriffin/New-Media-Image-Uploader) - Integrating the new media manager work-flow into your plugins/themes
-   [WordPress Transients Interface](https://github.com/markjaquith/WP-TLC-Transients) - A WordPress transients interface
-   [Logging Class](https://github.com/pippinsplugins/WP-Logging) - A general logging system
-   [Simple History](https://github.com/bonny/WordPress-Simple-History) - A logging tool with a pretty GUI. Logs user actions.
-   [WP Session Manager](https://github.com/ericmann/wp-session-manager) - Session manager for WordPress
-   [WP CoffeeScript](http://wordpress.org/plugins/wp-coffeescript/) - Use CoffeeScript in WordPress
-   [Dynamic Image Resize](https://github.com/franz-josef-kaiser/Dynamic-Image-Resize) - Resize images on the fly (like WPThumb/TimThumb but using PHP only)
-   [CleverRules](https://github.com/Giuseppe-Mazzapica/CleverRules) -  New way to handle rewrite rules
-   [TGM Plugin Activation](https://github.com/TGMPA/TGM-Plugin-Activation) - Drop-in class to require and/or recommend plugins for Themes and Plugins (dependency management). You can reference bundled plugins, plugin from the WP repo and externally hosted plugins. See [their website](http://tgmpluginactivation.com/) for more information.
-   [WP Requirements](https://github.com/nekojira/wp-requirements) - A little utility class template to adapt in your plugin project to help you check for WP version, PHP version and PHP extensions before letting users activate a plugin that has minimum requirements.
-   [Auto login](https://github.com/szepeviktor/auto-login) - An MU plugin to log in without username and password. A username should be `define()`-d in wp-config.
-   [SMTP URI](https://github.com/szepeviktor/smtp-uri) Quickly set up SMTP. "smtp://localhost:2525"


* * * * *

Meta Fields 
---------------

##### Meta data stuff (custom fields, meta fields, meta boxes, etc)

-   [Advanced Custom Fields](https://www.advancedcustomfields.com) - Plugins to help create custom fields easily using GUI.
-   [My-Meta-Box](https://github.com/bainternet/My-Meta-Box) - Class for creating custom meta boxes
-   [Meta Box Plugin](https://github.com/rilwis/meta-box) - Easily create custom meta boxes
-   [Custom Metaboxes 2 *aka* CMB2](https://github.com/WebDevStudios/CMB2) - WebDevStudios  
-   [WpAlchemy](https://github.com/farinspace/wpalchemy) - Thin meta framework
-   [SuperCPT](https://github.com/mboynes/super-cpt) CPT and meta box wrapper with icons
-   [WordPress Taxonomies Fields](https://github.com/bainternet/Tax-Meta-Class) - WordPress taxonomies custom fields
-   [Automattic's Custom Metadata](https://github.com/Automattic/custom-metadata) - Add custom fields to your object types
-   [Custom Meta Boxes](https://github.com/humanmade/Custom-Meta-Boxes) - Humanmade's metaboxes with custom fields that will blow your mind
-   [Field Manager](http://fieldmanager.org/) - Fieldmanager is a toolkit for developers to create complex administration screen
-   [Sunrise](https://bitbucket.org/newclarity/sunrise-1) - New Clarity's Admin Post Forms & Fields
-   [Developers Custom Fields](https://github.com/gyrus/WordPress-Developers-Custom-Fields) - Tools for managing custom fields
-   [Simple Fields](https://github.com/bonny/WordPress-Simple-Fields)- Simple Fields
-   [Page Type API](http://wp-papi.github.io/) - Papi has a different approach on how to work with fields and page types in WordPress.

 
* * * * *

Theme Stuff
---------------

##### Theme tools and boilerplate

-   [Theme Customizer Controls](https://github.com/paulund/Wordpress-Theme-Customizer-Custom-Controls) - Custom controls for your theme customizer page
-   [Kirki Toolkit](https://github.com/aristath/kirki) - Custom controls & API for the Customizer
-   [Wordless](https://github.com/welaika/wordless) - Haml, Compass and Coffeescript (Ruby)
-   [Forge](https://github.com/thethemefoundry/forge) - Sass, LESS, and CoffeeScript (Ruby)
-   [Compass WordPress](https://github.com/pengwynn/compass-wordpress) - Sass
-   [Grunt-WP-Theme](https://github.com/10up/grunt-wp-theme) - Grunt Scaffold (node)
-   [Prometheus](https://github.com/noeltock/prometheus) Front-end foundation (LESS, wpthumb)
-   [WordPress Template Base](https://github.com/wycks/WordPress-Template-Base) File structure based on several themes and template hierarchy
-   [Theme-Check](http://wordpress.org/plugins/theme-check/) - Test your theme and make sure it's up to spec
-   [Monster Widget](http://wordpress.org/plugins/monster-widget/) - Provides a quick and easy method of adding all core widgets to a sidebar for testing purposes.
-   [Timber](http://github.com/jarednova/timber) - Write your theme using Twig templates (similar to Mustache, Handlebars, etc.)
-   [Cutlass](https://github.com/zach-adams/cutlass-wp-theme) - Develop your theme using Laravel's Blade Templating Engine
-   [Sprig](https://github.com/zach-adams/sprig) - Develop your theme using the Twig Templating Engine (similar to Timber)

If you are looking for theme option frameworks, look above under "Framework stuff".


* * * * *

Internationalization & Localization Stuff
---------------

##### Helper plugins

-   [Pig Latin](https://wordpress.org/plugins/piglatin/) - Changes all text strings into Pig Latin to easily spot which strings don't use localization functions.
-   [RTL Tester](https://wordpress.org/plugins/rtl-tester/) - Test your themes and plugins in Right-to-Left mode.
