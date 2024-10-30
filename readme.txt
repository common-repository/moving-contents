=== Moving Contents ===
Contributors: Katsushi Kawamori
Donate link: https://shop.riverforest-wp.info/donate/
Tags: comments, pages, posts, media, moving
Requires at least: 4.6
Requires PHP: 8.0
Tested up to: 6.6
Stable tag: 1.11
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Supports the transfer of Contents between servers.

== Description ==

Supports the transfer of Contents between servers.

= Export =
* Outputs the database as a JSON format file.
* Send the exported JSON file by e-mail.

= Import =
* It reads the exported JSON format file and outputs it to the database.
* Have the option to replace contents user IDs with the current user IDs.
* Have the option to replace all contents URLs.
* Have the option to replace all guid URLs.

= Maintain the following =
* ID
* user ID
* Date and time
* Posts
* Pages
* Comments
* Categories
* Tags
* Taxonomy
* Media Library(Database only)

= Sibling plugin =
* [Moving Users](https://wordpress.org/plugins/moving-users/).
* [Moving Media Library](https://wordpress.org/plugins/moving-media-library/).

== Installation ==

1. Upload `moving-contents` directory to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

none

== Screenshots ==

1. Export
2. Import

== Changelog ==

= [1.11] 2024/05/26 =
* Fix - Fixed problem with import files not being copied.

= [1.10] 2024/03/05 =
* Fix - Changed file operations to WP_Filesystem.

= 1.09 =
Changed the way files are read/written.

= 1.08 =
Supported WordPress 6.4.
PHP 8.0 is now required.

= 1.07 =
Supported WordPress 6.1.

= 1.06 =
Added option to replace all guid URLs.

= 1.05 =
Added a link to the sibling plugin.
Export log optimization.
Send the exported JSON file by e-mail.

= 1.04 =
Added an option to change the execution time of the import.

= 1.03 =
Enabled to output multiple JSON files.

= 1.02 =
Fixed translation.

= 1.01 =
Fixed translation.

= 1.00 =
Initial release.
