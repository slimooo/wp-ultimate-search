WP Ultimate Search
==================

Powerful AJAX-based search alternative which supports faceting queries by taxonomies, terms, and post meta data.

<h4>Description</h4>

WP Ultimate Search: a highly customizable WordPress search alternative with the ability to autocomplete [faceted search queries](http://en.wikipedia.org/wiki/Faceted_search).

Try a [demo](http://ultimatesearch.mindsharelabs.com/).

<h4>Features</h4>

* Searches post title and body content
* Can search by multiple keywords, and by full phrases
* Highlights search terms in results
* Option to send search queries as events to your Google Analytics account
* Facets by post category
* Can search in multiple categories (OR search)
* Category options are dynamically generated and autocompleted as you type
* Attractive and lightweight interface based on jQuery, Backbone.js, and the VisualSearch.js library
* Customizable results template using standard WordPress functions

Premium version now supports the ability to search through an unlimited number of user-specified taxonomies and meta fields (including data contained in Advanced Custom Fields)

<h4>Installation</h4>

1. Upload the `wp-ultimate-search` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Add a shortcode to a post, use the template tag in your theme, or use the sidebar widget.

For additional information, [visit our website](http://mindsharelabs.com/)

<h4>Changelog<h4>

v1.5.1
------------------------
* Values will no longer appear in dropdown if they're already in use in the search bar
* Fixed shortcode outputting contents at top of page
* Value dropdown will no longer appear when navigating to results page via permalink

v1.5
------------------------
* Added ability to search for posts by user
* Added ability to confine all searches to a single facet
* Added ability to only allow facets to be used once
* Added option to disable permalink generation
* Refactored database query for faster response times
* Fixed bug where multiple parameters wouldn't be received from permalinks
* Fixed bug where URL wouldn't reset when 'clear search' was clicked
* Fixed broken "results page" dropdown
* Misc. style fixes and normalizing

v1.4.5
------------------------
* Fixed bug with text searches

v1.4.4
------------------------
* Updated visualsearch.js to latest version
* Can now specify remainder preface for text queries
* Settings will now be set to defaults on first install
* Fixed extra history state being added when navigating to results page from widget
* Moved screenshots to /assets/ folder

v1.4.3
------------------------
* Fixed bug that prevented radius searches from working properly
* Fixed bug that broke in-page anchors on some sites
* Misc. bugfixes

v1.4.2
------------------------
* Updated options framework to work with new admin styles
* Simplified pro upgrade process
* Fixed typo in installation instructions
* Fixed bug caused by ampersands in permalinks
* Fixed PHP notices on multisite installations

v1.4.1
------------------------
* Fixed PHP warnings

v1.4
------------------------
* Added radius search capability based on ACF Map field
* Added ability to confine taxonomy searches to given terms
* Added ability to exclude specific post types from results
* Added ability to search for addresses stored with an ACF Map field
* Added ability to disable autocomplete per facet
* Fixed bug where spaces in facet names would break permalinks
* Fixed bug where permalinks weren't updated when last facet was removed
* Fixed bug where lowercase terms would appear after capitalized ones
* Fixed bug where pressing backspace would sometimes cause the browser to navigate back
* Fixed bugs that sometimes prevented premium upgrade

v1.3
------------------------
* Added the ability to search for posts based on their ACF checkboxes
* Added support for ACF comboxboxes
* Upgraded to EDD for licensing and upgrade
* Added settings to plugin action links

v1.2.1
------------------------
* Misc. bugfixes to 1.2

v1.2
------------------------
* Added an alternative square search bar style
* Added option to disable built-in taxonomies and revert to a plain text search
* Added option to restrict script loading to only pages with search bar
* Improved iOS support
* Fixed bug where tag search wouldn't work for some users
* Fixed "clear search" icon not clearing results
* Fixed wpdb->prepare() notice appearing in WP 3.6
* Fixed dropdown items appearing outside of search bar when a term was deleted
* Added browser navigation history when moving from widget to results page
* Minified visualsearch.js script

v1.1
------------------------
* Added support for special characters in facet values
* Fixed permalinked searches rendering spaces as underscores
* Fixed bug that would cause the "no results" message to not show
* Removed iOS/Safari warning message. Update to Safari has fixed the bug.
* Added Clear Search Results button option
* Added option to disable the facet options popping up on first focus
* Added option for placeholder text in the search bar
* Fixed bug where search results page wouldn't load on sites without pretty permalinks
* Added option to disable search results highlighting
* DB queries updated to support Wordpress 3.6
* Misc. style refinements and bugfixes

v1.0.3
------------------------
* Updates to premium upgrade process
* Removed premium 'teasers' from options page to comply with repository guidelines

v1.0.2
------------------------

WARNING: If you encounter any problems with this update, check the "Reset options" box and hit Save Changes to restore initial settings.

* Increased load times
* Silenced PHP notices when wp_debug was turned on
* Fixed bug that prevented option saving with some database configurations

1.0.1
------------------------
* Bugfix release:
* Minified spin.js
* Moved result highlighting out of php (buggy) and into JS
* Fixed bug where warnings would be issued on sites with no eligible meta fields
* Removed debugging function in visualsearch.js that occasionally caused conflicts with other scripts
* Updated visualsearch.js to v0.4.0
* Added default styling to search bar so bar will be displayed before scripts have loaded 

v1.0
------------------------
* Option to replace WordPress default search
* Ability to search in custom taxonomies (with upgrade)
* Ability to search in post meta fields (with upgrade)
* Searches now generate permalinks
* Supports user-created search results templates
* Many more tweaks and optimizations

v0.4
------------------------
* Can search post tags
* Optimized database interaction

v0.3
------------------------
* Added options page
* Ability to search within shortcodes
* Google Analytics integration
* Can search by multiple categories (OR)
* Option to put scripts in header or footer
* Will throw an error if search results shortcode isn't present on page
* Loading animations
* Fixed bug where widget wouldn't display on home page
* Misc. performance tweaks

= 0.2 =
* First public release
