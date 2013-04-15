=== Envato Items ===
Contributors: butterflymedia, getbutterfly
Tags: envato, envato api, themeforest, codecanyon, graphicriver, recent, items
License: GPLv3
Requires at least: 3.0
Tested up to: 3.6-beta1
Stable tag: 1.1

== Description ==

Display your Envato portfolio inside a post or a page.

Shortcode parameters:

`type` ('compact' or 'loose') - show or hide name and price
`username` ('your-username')
`market` ('codecanyon' or 'themeforest' or 'graphicriver')
`price` (true) - show or hide price
`ref` ('your-referral-username')
`currency` ('$')
`count` (0) - set to 0 to display all

`[envato type="compact" username="butterflymedia" market="codecanyon" price="false" ref="butterflymedia" currency="$" count=0]`

Style `.envato-container` class to override the current loose style.

== Installation ==

1. Upload the plugin folder to your `/wp-content/plugins/` directory
2. Activate the plugin via the Plugins menu in WordPress
3. Create and publish a new page and add the shortcode

Note: Your server must support the php `file_get_contents()` function.

== Changelog ==

= 1.1 =
* First public release