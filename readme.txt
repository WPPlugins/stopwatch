=== Stopwatch ===
Contributors: luisperezphd
Donate link: 
Tags: stopwatch
Requires at least: 3.3
Tested up to: 3.4
Stable tag: 
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A stopwatch, start, stop, pause, etc.

== Description ==

A stopwatch from ipadstopwatch.com. It works on PC and mobile devices. It adjusts to any size. Very easy to use and keeps running after you leave which makes it perfect for measuring long running tasks that span hours, even days.

== Installation ==

1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Place `<?php do_action('plugin_name_hook'); ?>` in your templates

== How it works ==

The widget works by pulling in the stopwatch from the actual
ipadstopwatch.com site. This way the person can start and stop the 
stopwatch and stopwatch can continue working after the leave the site
by tracking the time in the ipadstopwatch.com cookie.

More specifically it pulls in an HTML file into an iframe.