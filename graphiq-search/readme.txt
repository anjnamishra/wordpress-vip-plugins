=== Graphiq Search ===
Contributors: Graphiq
Donate link: https://www.graphiq.com/
Tags: graphiq, data, visualization, infographic, embed, widget, comparison
Requires at least: 2.7
Tested up to: 4.5
Stable tag: 3.2.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Add relevant, interactive visuals to any WordPress post.

== Description ==

Add relevant, interactive content to any WordPress post. Our plugin turns plain
text into visually engaging articles, with images, slideshows, side-by-side
comparisons, and deep details on people, organizations, products, and services.

To begin, click the "Add Visualizations" button above the post editor. If your post
contains any content, we'll begin searching for visuals that match what you're
writing about. From this interface you can also search for something specific,
see trending visuals, or browse by category. You can start a search from our
search box in the WordPress sidebar.

Once you've found the visual you want to use and customized it to your liking,
click "Add" button to insert this visual into your post. The content will
appear as a gray placeholder within your article. To see the content in action,
simply preview or publish your post.

The plugin includes over 1,500 topics (ex: Presidents), 500 million entities
(ex: Barack Obama), and billions of points of information (ex: Obama's
historical approval ratings compared to other presidents).

= Benefits =

* Engage readers with relevant, visual content.
* Add credibility to your posts. We've already done the research for you.
* Post content that looks great and matches your site. Customize the look, feel,
  and style of each visual.

== Installation ==

1. Upload the plugin folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Use the "Add Visuals" button above the editor to discover and add visuals.

== Screenshots ==

1. Begin by clicking "Add Visuals" or searching from the sidebar
2. We'll recommend visuals based on your article, but you can also search
3. Once you've found the right visual, add it to your post

== Changelog ==

= 3.2.4 =
* Removed requirement for title attribute to be present in shortcode

= 3.2.3 =
* Fix AMP violation, ensure all AMP styles appear in head element

= 3.2.2 =
* Fix AMP compatibility, remove require_once (Cheers to Stanko Metodiev for reporting!)

= 3.2.1 =
* Add support for AMP embed code (when using WP-AMP plugin)
* Default to wordpress shortcodes when embedding a story asset

= 3.2.0 =
* Add support for inserting stories–a new asset type!
* Switch to using javascript embed code, to support dynamic resizing of visaulizations
* Pass plugin version when making requests to Graphiqs search API

= 3.1.0 =
* Internal code restructuring for VIP

= 3.0.8 =
* Fix Graphiq URL references, minify standalone cms integration library

= 3.0.7 =
* More flexible data type handling for shortcodes

= 3.0.6 =
* Minor wording change for launch button

= 3.0.5 =
* Update plugin branding

= 3.0.4 =
* Better validation and syntax for Wordpress VIP coding standards

= 3.0.3 =
* Removed use of extract for Wordpress VIP

= 3.0.2 =
* Add support for "Page" post type

= 3.0 =
* Significant overhaul, rebranding as the "Visual Search" plugin
* Begin indexing full breadth of content and visuals
* More descriptive widget placeholders when editing post
* Add optional API Key support for premium partners

= 2.2.1 =
* Fix iframe API interface with graphiq application

= 2.2 =
* Add HTTPS/SSL support
* Add support for dealing with rate limited requests

= 2.1 =
* Remove use of namespaces to support PHP 5.3
* Optional support for custom post types
* Fix image resource paths

= 2.0 =
* Full revamp from initial version 1.0
