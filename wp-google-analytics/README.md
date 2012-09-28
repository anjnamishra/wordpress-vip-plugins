# WP Google Analytics

Lets you use <a href="http://analytics.google.com">Google Analytics</a> to track your WordPress site statistics.  Brought to you by <a href="http://ran.ge">Range</a>

## Description

Lets you use <a href="http://analytics.google.com">Google Analytics</a> to track
your WordPress site statistics.  It is easily configurable to:

* Not log anything in the admin area
* Log 404 errors as /404/{url}?referrer={referrer}
* Log searches as /search/{search}?referrer={referrer}
* Log outgoing links as /outgoing/{url}?referrer={referrer}
* Not log any user roles (administrators, editors, authors, etc)

## Installation

Use automatic installer.

## Frequently Asked Questions

**Where do I put my Google Analytics Code?**

WP Google Analytics has a config page under the settings tab in the admin area
of your site.  You can paste your tracking code from Google into the textarea on
this page.

**Can't I just paste the Google Analytics code into my template file?**

Absolutely, however in order to get a better idea of what is going on with your
site, it is often nice to have your own activities ignored, track 404s, searches
and even where users go when they leave your site.  WP Google Analytics lets you
easily do all these things.


## Changelog

### 1.2.5
* Fixed some notices. Props westi
* Update all links

### 1.2.4
* Removed the optional anonymous statistics collection.  Nothing is ever collected anymore.
* Changed & to &amp; in some more places to fix validation problems.

### 1.2.3
* Changed & to &amp; to fix validation problems.

### 1.2.2
* Fixed problem with code affecting Admin Javascript such as the TinyMCE editor

### 1.2.1
* Bug fix for the stats gathering

### 1.2.0
* No longer parses outgoing links in the admin section.
* Uses get_footer instead of wp_footer.  Too many themes aren't adding the wp_footer call.
* Options page updated
* Added optional anonymous statistics collection

### 1.1.0
* Major revamp to work better with the new Google Tracking Code.  It seems that outgoing links weren't being tracked properly.

### 1.0.0
* Added to wordpress.org repository

### 0.2
* Fixed problem with themes that do not call wp_footer().  If you are reading this and you are a theme developer, USE THE HOOKS!  That's what they're there for!
* Updated how the admin section is handled

### 0.1
* Original Version